# Optics_VLab

A high-fidelity, interactive physics simulation designed to visualize and calculate optical phenomena through a virtual lens bench. This tool leverages analytical ray tracing to provide an accurate educational experience for understanding geometric optics.

---

## 🚀 Key Features

### 🔬 Physics Engine
The simulation is built on rigorous mathematical foundations rather than visual approximations:
* **Gaussian Thin Lens Formula**: Implements the fundamental equation:
    $$\frac{1}{f} = \frac{1}{u} + \frac{1}{v}$$
* **Analytical Ray Tracing**: All ray intersections and trajectories are calculated mathematically for pixel-perfect accuracy.
* **Dual Lens Support**: Full support for both **Convex** (converging) and **Concave** (diverging) lenses with authentic physical behavior.

### 🖱️ Interactive Elements
* **Dynamic Manipulation**: Drag the candle object horizontally to instantly observe changes in image formation.
* **Adjustable Optics**: Focal points (marked with **×**) can be dragged to modify the lens power in real-time.
* **Precision Control**: Fine-tune parameters via dedicated sliders for specific experimentation.
* **One-Click Demo**: An automated animation sequence that cycles the object from $4f$ to $0.6f$, showcasing all standard imaging cases.

### 🎨 Visual Design
The interface utilizes a **dark technical aesthetic** with a high-contrast color palette for clarity:
* 🟡 **Gold/Yellow**: Incident rays
* 🟢 **Green**: Refracted rays
* 🔘 **Gray Dashed**: Virtual ray extensions
* 💎 **Cyan**: Image representation (Solid for Real, Dashed for Virtual)

---

## 📊 Real-Time Data & Analytics
The simulation features a dynamic data panel that updates instantaneously as you interact with the scene:
* **Calculated Metrics**: Image distance ($v$), Magnification ($M$), and Image height.
* **Dynamic Property Badges**: Visual indicators that automatically classify the image:
    * **Type**: Real vs. Virtual
    * **Orientation**: Upright vs. Inverted
    * **Scale**: Magnified vs. Reduced

---

## 📐 Ray Drawing Logic

### Convex Lens (Converging)
* **Parallel Ray**: Enters parallel to the axis, exits through the far focal point.
* **Central Ray**: Passes through the optical center without deviation.
* **Focal Ray**: Passes through the near focal point and exits parallel to the axis (when $u > f$).

### Concave Lens (Diverging)
* **Parallel Ray**: Enters parallel and diverges such that its extension passes through the virtual focal point.
* **Central Ray**: Passes through the optical center without deviation.
