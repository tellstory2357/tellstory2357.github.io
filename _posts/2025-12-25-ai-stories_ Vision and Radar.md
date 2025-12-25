# AI Chronicles 3: Vision and Radar — The Evolution of the “Eyes” of Autonomous Driving

I’ve always thought my brain worked pretty well—until I sat in the driver’s seat and realized that driving isn’t about solving math problems, but a kind of *street survival game* that requires juggling a dozen variables at once. So when autonomous driving claimed it could take over this mess, I was immediately intrigued: **how does a machine actually learn to “see the road”?**

It turns out it mainly relies on two systems: **vision algorithms and radar**. Together, they’re like a sharp-eyed detective paired with a bodyguard who can see in the dark.

---

## I. Vision Algorithms: Three Real Upgrades from “Seeing” to “Understanding”

### First upgrade: Installing “visual nerves”
Around 2012, breakthroughs in **convolutional neural networks (CNNs)** allowed AI to truly recognize objects from pixels. It was like giving computers a primitive visual cortex. Instead of being told that “cars have wheels,” the system could infer the concept of a *car* on its own from massive numbers of images.

### Second upgrade: Gaining a “god’s-eye view”
Recognizing objects isn’t enough—you also need to know **where** they are. **BEV (bird’s-eye view) perception** reconstructs multiple 2D camera images into a unified 3D top-down view, giving vehicles a video-game-like god’s-eye perspective to judge positions and distances accurately.

### Third upgrade: Learning to “think and predict”
More recently, **Transformer architectures** crossed over from NLP into vision. With attention mechanisms and massive real-world driving data, AI began to understand scene logic—for example, predicting whether a pedestrian might run a red light.

Yet vision has a fatal weakness: **darkness**. Heavy rain, glare, or pitch-black nights can leave cameras blind. That’s when its partner steps in.

---

## II. Radar: The Ever-Awake “Night Watchman”

Radar doesn’t rely on light. It emits electromagnetic waves and detects objects by analyzing echoes, directly measuring distance and speed. Its greatest strength is **stability**—no matter how bad the weather or how dark the night, radar can reliably detect obstacles.

Its weakness is resolution. Radar can usually tell you *something* is ahead, but not whether it’s a deer or a billboard. That’s why **vision-led, radar-assisted sensor fusion** has become the mainstream approach.

---

## III. The “Ceiling” of the Veteran Driver

All of this ultimately depends on **data**. Every autonomous vehicle is constantly accumulating experience, like a novice driver growing into a veteran. But learning eventually slows: rapid gains early on, then diminishing improvements as the system approaches a capability ceiling.

We haven’t reached that ceiling yet. Today’s autonomous driving systems are still frantically collecting experience and fixing rare edge cases. Perhaps true maturity will come when they can genuinely understand warnings like, *“Watch out for that kid about to pop out.”*

So my car-buying criteria are simple: **top-tier vision + radar fusion, and a brain that keeps learning**. Until then, I’ll keep my hands on the steering wheel.
