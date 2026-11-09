# Adnan Khan

BS Mechanical Engineering — Binghamton University · Queens, NY

I build simulation tools. My main project is [Astraea](https://astraea-5e2.pages.dev/), an open-source rocket engineering workstation — 3D airframe design, Rust/WASM 6-DOF flight simulation, Monte Carlo dispersion, and comparison against real flight logs. I also build [RecoverySys](https://akhan157.github.io/RecoverySys/), a local-first recovery-bay planner, and [Plainhand](https://github.com/akhan157/Plainhand), a job-application assistant that runs on your own computer.

---

## Background

**Rocketry (Aerobing Team, Binghamton)** — Led a 4-person dual-deploy recovery system build from design through fabrication (carbon fiber, black powder assembly, precision machining). Separately, ran FEA stress analysis on a composite pressure tester: 308K+ nodes, cross-validated against hand calculations, applied ASME pressure vessel and ASTM D3039 standards. Factor of safety of 3.14 at 2,000 psi working pressure.

**NYC DEP (Mechanical Engineering Intern, 2024–2025)** — Designed sewer infrastructure plans in AutoCAD, investigated chronic failures using GIS and CCTV inspection data, and built a digital inspection database that automated maintenance scheduling. Also inspected backflow prevention assemblies across all five boroughs.

**Formula SAE** — Designed suspension components (rotors, tabs) in coordination across drivetrain and steering teams.

---

## What I'm building toward

My simulation work sits at the edge of where physics-based models meet machine learning — surrogate models, physics-informed neural networks, fast approximate simulation. recoverysys-surrogate is now shipped: a neural network trained on 2,000 physics-engine simulations that predicts flight outputs in about 2 µs per sample, roughly 22,000× faster than the solver. That's the direction.

---

**Engineering:** SOLIDWORKS · ANSYS · FEA · MATLAB · SciPy · AutoCAD

**Software:** Python · JavaScript · React · FastAPI · Vite · Git

**Fabrication:** MIG/TIG welding · carbon fiber layup · precision machining · 3D printing

---

## Projects

**[Astraea](https://github.com/akhan157/astraea)** — Open-source rocket engineering workstation: 3D airframe design, Rust/WASM 6-DOF flight simulation, Monte Carlo dispersion, and comparison against real flight logs. 0.10 beta; validation in progress. [Live →](https://astraea-5e2.pages.dev/)

**[RecoverySys](https://github.com/akhan157/RecoverySys)** — Recovery-first, local-first recovery-bay planning and flight-estimation tool for high-power rocketry. 225-part catalog with compatibility and load-path checks, Monte Carlo dispersion, and a printable recovery brief. [Live →](https://akhan157.github.io/RecoverySys/)

**[Plainhand](https://github.com/akhan157/Plainhand)** — Job-application assistant that runs on your computer with your own AI account. Builds a profile in your own words, tailors resumes and cover letters, and fills application forms; you review and submit every application.

**[recoverysys-engine](https://github.com/akhan157/recoverysys-engine)** — High-fidelity recovery simulation engine for high-power rocketry. Python, SciPy, FastAPI.

**[recoverysys-surrogate](https://github.com/akhan157/recoverysys-surrogate)** — Neural network surrogate model for the RecoverySys engine. Trained on 2,000 physics-engine simulations; about 2 µs per sample versus ~45 ms for the solver, a ~22,000× speedup.

---

[LinkedIn](https://linkedin.com/in/adnank157) · adnank11427@gmail.com
