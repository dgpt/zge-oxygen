# zge-oxygen
ZGameEditor visualization of an oxygen atom.

## Controls
The FL Studio ZGameEditor UI exposes the following parameters:

1. Audio Gain
2. Nucleus Sensitivity
3. Orbital Sensitivity
4. Smoothness
5. Animation Speed
6. Orbital Size
7. Density Gain
8. Nucleus Radius
9. Nucleus Dot Size
10. Proton HSLA
11. Neutron HSLA
12. Orbital+ HSLA
13. Orbital- HSLA

All sliders default to 50% to ensure a visible render on load. The nucleus jitters with audio rather than changing size,
orbitals accelerate with sound instead of brightening, and each element has independent sensitivity and color controls.
Orbitals are now ray-marched volumetric clouds with soft edges and directional lighting, yielding a deeper three-dimensional
feel while remaining quantum-accurate. Animation speed offers a much wider range, and the background color is fixed at full
alpha and no longer user-adjustable.
