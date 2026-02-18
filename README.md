### Hi, I'm Basyirin. I make robots move precisely.

I am an R&D Engineer specializing in **Embedded Control Systems** and **Physics-Informed Machine Learning**. My work focuses on solving the "Reality Gap"—deploying intelligent agents onto hardware with strict latency constraints (<10ms).

I don't just train models; I deploy them to the metal.

---

### 🛠️ Technical Arsenal

| Domain | Technology | Use Case |
| :--- | :--- | :--- |
| **Control & Dynamics** | PID, LQR, System ID | Stabilizing unstable systems |
| **Embedded Firmware** | C++, PlatformIO, FreeRTOS | Hard real-time execution (Teensy 4.1, ESP32) |
| **Scientific ML** | PyTorch, JAX, ONNX | Physics-Informed Neural Networks (PINNs) |
| **Simulation** | Differentiable Physics | Sim-to-Real transfer & Domain Randomization |

---

### 🔭 Current Research: FastTrack
**Project:** [PIRL_Adaptive_Control](https://github.com/basyirin-dev/PIRL_Adaptive_Control)
* **The Challenge:** Eliminating non-linear Stribeck friction in actuators without manual tuning.
* **The Solution:** A hybrid controller combining classical PID with a residual Physics-Informed Neural Network.
* **The Constraint:** Inference must happen in **<500 microseconds** on a microcontroller.
* **Status:** Phase 2 (Hardware Verification).

---

### 📈 Philosophy
> **"We do not learn the robot; we learn the rust."**
> Reliable control isn't about modeling the perfect physics; it's about robustly rejecting the imperfections (friction, noise, latency) that simulation misses.
