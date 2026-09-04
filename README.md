<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/msannikov03/msannikov03/main/assets/header-dark.svg">
  <img alt="Mikhail Sannikov — ML research, robotics" src="https://raw.githubusercontent.com/msannikov03/msannikov03/main/assets/header-light.svg" width="100%">
</picture>

I work on robot learning — manipulation policies, tactile sensing, and the software
that makes them reproducible. Most of what I build is meant to be installed and run
by someone else in under a minute, not cloned and fought with.

---

### Shipped

**[Caliper](https://github.com/msannikov03/caliper)** — one deterministic Rust core for serial-arm robotics,
published as **17 crates** and exposed through three faces that share the exact same code:
a CLI, a Python module built with maturin, and *Caliper Studio*, a Tauri + React desktop
app with a 3D scene and a Simulink-style dataflow editor. Kinematics, IK, dynamics,
collision, planning, trajectory optimization and MuJoCo contact sim all sit behind one
API, so the shell, the notebook and the GUI can't drift apart. Ships as an 11 MB signed
and notarized dmg with the physics inside — no ROS workspace, no GPU, no cloud.

&nbsp;&nbsp;&nbsp;&nbsp;`crates.io` · `Apache-2.0` · [docs](https://msannikov03.github.io/caliper/) · `cargo install caliper-cli`

**[Wisp](https://sannikov.club/wisp)** — a macOS menu-bar app that puts your iPhone anywhere on Earth.
Vector-tile basemap with no API key and no rate limit, so it can't be throttled into a
"key required" screen. Every build goes out through a Sparkle feed Apple-notarized *and*
EdDSA-signed, so only genuine builds install.

**[Daily Manifesto](https://apps.apple.com/us/app/daily-manifesto/id6799500382)** — iOS, live on the App Store. A return engine rather than
a to-do list: timed drops, a widget that changes state through the day, on-this-day
resurfacing, and a 45-day cycle that decides what comes back next. The scheduling logic
carries 103 tests because getting the *when* wrong is the whole failure mode.

**[Lectrum](https://apps.apple.com/us/app/lectrum/id6803515077)** — iOS, live on the App Store. SwiftUI + SwiftData capture that ranks
ideas by importance and resurfaces them instead of burying them, synced through CloudKit
with the production schema verified field-for-field against development before release.

---

### Research

| | | |
|---|---|---|
| **[ScaffDiff](https://sannikov.club/research)** | IEEE SMC 2026 · accepted | dense 3D scenes from sparse LiDAR, in a single denoising step |
| **[HapticVLA](https://sannikov.club/research)** | IROS 2026 · accepted | contact-rich manipulation with no tactile sensor at inference |
| **[Phantom](https://sannikov.club/research)** | ICRA 2027 · in progress | a world model that feels the contact coming before it happens |

---

### Currently

Robot learning — teacher/student policies for contact-rich manipulation, tactile-conditioned
control, and getting the deploy path to behave like the training path. Open to ML and
robotics engineering roles.

---

**[sannikov.club](https://sannikov.club)** · [msannikov03@icloud.com](mailto:msannikov03@icloud.com)
