Pendulum Visual Controller

Live Demo: https://anoyume91.github.io/pendulum-visual-controller/

An interactive pendulum simulation where the pendulum's motion
(angle, speed, damping, and direction) drives several different visual modes.
The project explores how a simple physical system can be used to generate
a variety of dynamic graphics and behaviours.

Overview:
The visualization is based on a single pendulum model. Its state values
(angle, angular velocity, acceleration) control multiple visual modes such as:

- waveform trails influenced by pendulum motion
- particle fields that react to angle and velocity
- geometric and mandala-style shapes
- simple energy-based visual patterns

The project includes basic interaction such as dragging, switching modes,
toggling damping, and adjusting parameters.

Physics Model:
The pendulum follows the standard simplified equation of motion:

  angular acceleration = –(g / length) * sin(angle) – damping * angular velocity

The motion is updated using a straightforward Euler integration loop.

Controls:
- Drag the bob to set the initial angle
- Space: switch visualization mode
- D: toggle damping
- R: reset pendulum
- Scroll: adjust pendulum length

Technologies used:
- JavaScript
- p5.js
- HTML / CSS


