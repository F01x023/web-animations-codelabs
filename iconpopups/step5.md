## Step 5: Fading it all in

The effect we've generated looks cool, but it has a clear issue - the icons being displayed are immediately visible, while the effect has a short duration.

Instead of showing each icon immediately, let's fade them in over time. The top icon can fade immediately, followed by the next icon, and so on. We can achieve this using a `SequenceEffect` (for each icon), and a `GroupEffect` (to combine with the reveal effect). The layout of our animations will look a bit like this-

![Groups](resources/step5-groups.png)

Let's get started!
