# Empty Platformer project - Documentation - `Particles Target`

Modify particles emission shape to move them smoothly to a given target.

![`Particles Target` component inspector](./images/particles-target.png)

![`Particles Target` component preview](./images/particles-target-example.gif)

## Parameters

- **Particle System**: The reference to the `Particle System` component affected by this effect.
- **Target**: The position to which the particles will move.
- **Lerp**: The linear interpolation amount from the current particle position to the target the particles will move along each frame.
- **Affect Particles Delay**: Defines the particles before this component affect the particles position. Before this delay, the particles will ask as they normally do from the Particle System.

---

[<= Back to summary](./README.md)