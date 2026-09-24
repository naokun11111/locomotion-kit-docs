# Dinosaur & Animal Locomotion Kit — documentation

Documentation for the **Dinosaur & Animal Locomotion Kit**, a locomotion plugin for
Unreal Engine 5.5.

**Read it here: https://naokun11111.github.io/locomotion-kit-docs/**

A large animal cannot pivot on the spot. At a given speed its body can only come round so
fast, so it walks an arc. This kit gives any Character that arc — and then draws the arc it
actually walked, so you can check it against the one you asked for.

- Turning radius, blended by speed, with an optional third control point for trot
- Turn in place — standing still, it steps round rather than sliding
- Crouching that drives the engine's own crouch (capsule, speed cap, replication)
- Ground adaptation, head aim, attacks, growth stages
- Set-up is one tick box: it reads your skeleton and tells you every guess it made

Full C++ source. No Animation Blueprint required.

The kit ships with **no character content**. No meshes, no animations, no creature — you
point it at your own Skeletal Mesh and your own clips.

---

This repository contains the manual only. Report a problem with the documentation by
opening an issue.
