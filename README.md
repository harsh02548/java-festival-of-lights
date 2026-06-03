This project is a multi-tiered Java application utilizing `Graphics2D` to render a festive home environment. Users can interact with the environment to trigger holiday lights, scale interactive elements, adjust lighting gradients based on mouse positions, and unlock a special cultural greeting.

---

## 🎮 Controls & Challenge Guide

### 🔹 Level 1: Interactive Basics

#### **Challenge 1: Window Illumination**
* **Controls:** Move your mouse cursor inside the boundaries of the house structure ($X: 200 \rightarrow 600$, $Y: 300 \rightarrow 600$).
* **Action:** The windows of the house switch from unlit white to a bright festive yellow when hovered over.

#### **Challenge 2: Number-Key Light Strands**
* **Controls:** Press and hold number keys `1` through `5` on your keyboard.
* **Action:** Spawns targeted vertical light lines decorated with red, blue, and green oval micro-lights across specific structural coordinates of the house.
  * `1` - First string (Left edge)
  * `2` - Second string
  * `3` - Third string (Center)
  * `4` - Fourth string
  * `5` - Fifth string (Right edge)

#### **Challenge 3: Brightness Intensifier Roof Lights**
* **Controls:** Click and hold the **Left Mouse Button**.
* **Action:** Strands of lights running along the base of the roof transition instantly from their default dim states (`darkBlue`, `darkRed`, `darkGreen`) to vibrant, fully saturated bright states (`Color.blue`, `Color.red`, `Color.green`). Releasing the button resets them.

---

### 🔸 Level 2: Advanced Mechanics & Scaling

#### **Challenge 1: Drag-and-Drop Rocket Firework**
* **Controls:** Click and hold inside the rectangular rocket base ($X \approx 100$, $Y \approx 550$), drag your mouse, and release.
* **Action:** Picks up and repositions a multi-colored (White, Red, Blue, Brown) rocket firework anywhere across the canvas. It remains safely fixed in place wherever you release it.

#### **Challenge 2: Key-Scaled Shadow Light Mask**
* **Controls:** Press and hold `B` to grow; press and hold `S` to shrink.
* **Action:** Adjusts the bounding size ($X_1, Y_1$) of a contrasting black oval mask pinned to the top-left section of the canvas, altering the light footprint dynamically.

#### **Challenge 3: Horizontal Gradient Oil Lamp (Diya)**
* **Controls:** Move your mouse horizontally across the screen from left ($X = 0$) to right ($X = 800$).
* **Action:** Dynamically tracks your horizontal position to step-increment an integer color value (`cooler`) between $0$ and $255$. This shifts the flame matrix of the drawn lamp from dark pitch black to an intensely brilliant fiery red.

---

### 🎉 Level 3: Overlap & Celebration Finale

#### **Challenge 1: The Diwali Box Unlocking**
* **Controls:** Click and drag the interactive red box ($X: 60, Y: 560$) into the target white drop-zone box positioned near the roof line ($X: 360, Y: 180$).
* **Action:** Triggers an intersection state that overrides the structural canvas to reveal a massive canvas burst displaying a bright red **"Happy Diwali!"** cultural text banner.
