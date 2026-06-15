<div align="center">

# V V Sai Sridhar

**Electronics & Communication Engineering · BITS Pilani, Goa Campus**

[Email](mailto:sridharvvs1124@gmail.com) · [LinkedIn](https://linkedin.com/in/saisridhar77) · [GitHub](https://github.com/saisridhar77)

</div>

---

## About

I am a third-year ECE undergraduate at BITS Pilani with interests spanning RTL design, embedded systems, real-time operating systems, and full-stack web development. I work across the hardware-software boundary — from writing synthesisable SystemVerilog and Linux kernel drivers to building production web applications.

Currently researching mixed-criticality real-time scheduling for AUTOSAR multicore platforms under Prof. Biju K. Raveendran.

---

## Work

**Research Intern — CSIR National Aerospace Laboratories** *(Jun – Jul 2025)*  
Designed cascaded PID control architectures for 6-DOF multi-rotor UAV attitude stabilisation in MATLAB/Simulink. Achieved under 5% overshoot and 0.8 s settling time across all axes via Bode-plot tuning.

**Head of Web Development — Developers' Society, BITS Goa** *(May 2025 – Apr 2026)*  
Led a 30-member team to deliver six production systems including an e-commerce platform and high-traffic fest portals. Introduced CI/CD pipelines and structured onboarding that reduced ramp-up time to four weeks.

---

## Selected Projects

### Hardware & Systems

**[Async FIFO with Gray-Code CDC](https://github.com/saisridhar77)**  
Depth-16 asynchronous FIFO with gray-code pointers and two-FF synchronisers on each clock-domain crossing. Self-checking SystemVerilog testbench covers full, empty, reset, and simultaneous read/write edge cases. SVA assertions for overflow, underflow, and single-bit gray transitions pass cleanly under VCS.

**[CDC Verification Framework](https://github.com/saisridhar77)**  
Three-layer CDC environment built on the async FIFO: SpyGlass static analysis, SVA monitors, and functional coverage. Resolved three structural violations and achieved clean sign-off. Non-intrusive CDC monitor bound via SystemVerilog `bind`; 100% functional coverage across all scenarios.

**[Out-of-Order RISC-V Processor](https://github.com/saisridhar77)**  
Superscalar out-of-order processor in Verilog using Tomasulo's algorithm end-to-end. Register Alias Table and Reorder Buffer eliminate WAR/WAW hazards and enable safe speculation. Synthesised on Artix-7 via Vivado; timing closure confirmed with post-synthesis LUT/FF utilisation reported.

**[Deterministic Real-Time Task Offloader](https://github.com/saisridhar77)**  
Linux character driver paired with bare-metal STM32 firmware to offload latency-critical host workloads. System jitter compressed to under 20 µs by routing payloads through a custom IOCTL, bypassing TTY overhead. Packed serialisation protocol handles correct data alignment between 64-bit Linux host and 32-bit MCU.

### Software & ML

**[Continuum Robot RL](https://github.com/saisridhar77)**  
Physics-based simulation environment for continuum robot end-effector control using Proximal Policy Optimisation. Designed reward functions and observation space to improve policy convergence.

**[SWD Store](https://github.com/saisridhar77)**  
Full-stack e-commerce platform enabling student clubs at BITS Goa to manage and sell products online. Built with Next.js, Node.js, and MongoDB; deployed in production.

---

## Technical Skills

| Domain | Tools & Technologies |
|---|---|
| HDL & Verification | SystemVerilog, Verilog, SVA, Synopsys VCS, SpyGlass CDC |
| FPGA & EDA | Xilinx Vivado, Cadence Virtuoso, LTSpice |
| Embedded & OS | STM32, FreeRTOS, Bare-Metal ISR, UART/SPI/I2C, Linux Device Drivers |
| Languages | C, C++, Python, ARM Assembly, JavaScript |
| Web | React, Next.js, Node.js, Express.js, MongoDB, Tailwind CSS |
| ML & Control | PyTorch, TensorFlow, MATLAB/Simulink, Reinforcement Learning |

---

## Education

**B.E. Electronics and Communication Engineering**  
Birla Institute of Technology and Science, Pilani — Goa Campus · CGPA 8.6 / 10 · 2023 – 2027

Relevant coursework: Digital VLSI Design · Computer Architecture · Operating Systems · DSP · Digital Design · Microprocessors & Microcontrollers · DSA · OOP · Control Systems · Computer Networks

---

<div align="center">
<sub>sridharvvs1124@gmail.com</sub>
</div>
