# TAO — Kung Fu Mirror

Real-time martial-arts training avatar: point the phone at yourself and a photoreal 3D Shaolin monk (Gaussian-splat avatar generated from a single photo) mirrors your movement live — pose solve in 0.05 ms on-device, 120 fps splat renderer on a Galaxy S23 Ultra.

## Download (Android)

**[⬇ tao.apk — 43 MB (recommended)](https://github.com/aeoniv/tao-releases/releases/download/phase1/tao.apk)**

Larger debug build (with on-screen metrics HUD): [tao-debug.apk — 126 MB](https://github.com/aeoniv/tao-releases/releases/download/phase1/tao-debug.apk)

Install: download on your phone → allow installs from unknown sources → open **TAO** → tap **Train with the Monk** → grant camera access.

## Demo

[Device clip from the Firebase Test Lab run](https://github.com/aeoniv/tao-releases/releases/download/phase1/ga_mirror_s23_clip.mp4)

## Status

Phase 1 (Mirror). Latest: spine coil + wrist twist + head tracking in the pose solver, One-Euro landmark filtering, zero-backend standalone mode (bundled monk avatar). Physics layer (MuJoCo PD-tracked humanoid) spiked and greenlit. iOS build pending (needs a macOS toolchain).
