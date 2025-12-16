# Interactive-B-zier-Curve-with-Physics-Sensor-Control
Overview
This project demonstrates an interactive cubic Bézier curve that dynamically responds to motion input, simulating the behavior of a rope influenced by physics. Using sensor data, such as gyroscope and accelerometer inputs, the curve adjusts in real-time, providing a visually engaging and realistic effect.
Mathematical Model
The core of the project is based on a cubic Bézier curve, defined by four control points. The curve's shape is determined by the positions of these points and the parameter t, which ranges from 0 to 1. As t varies, the curve interpolates between the control points, creating a smooth and flexible shape.
Physics Model
To emulate the rope-like behavior, we’ve integrated a simple physics model. The control points are influenced by motion input, where the acceleration and rotation data adjust the positions of these points. This creates a responsive and dynamic curve that mimics real-world physics, such as tension and elasticity.
Design Choices
In designing this project, we aimed for simplicity and performance. We chose a cubic Bézier curve because it provides smooth transitions and is computationally efficient. The physics model is kept lightweight to ensure real-time responsiveness on mobile devices.
Implementation Details
Control Points: The initial positions are set at the start, and they dynamically adjust based on sensor input.
Sensor Integration: We use the device’s gyroscope and accelerometer to capture motion data.
Rendering: The curve is rendered in real-time, updating as the sensor data changes.
What Wasn't Done
We chose not to implement complex physics simulations like full rope dynamics or collision detection to keep the project lightweight and responsive.
Demo Video
A short 15-20 second video is included in the repository to showcase the interactive Bézier curve in action. This video demonstrates how the curve responds to motion and highlights the real-time interaction.
