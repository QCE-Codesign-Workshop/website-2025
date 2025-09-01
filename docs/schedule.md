# Schedule

**Thursday, September 4, 2025**
Rooms 23/25 (Nambe/Navajo)

## Session 1: Device-aware simulation
**🕙 10:00 – 11:30 MDT**  
**Chair:** Tina Oberoi  

<details>
  <summary><strong>10:00 – 10:15</strong> Taylor Lee Patti (NVIDIA)</summary>
  <p><em>Title:</em> Augmenting Simulated Noisy Quantum Data Collection by Orders of Magnitude Using Pre-Trajectory Sampling with Batched Execution</p>
  <p><em>Abstract:</em> </p>
</details>

<details>
  <summary><strong>10:15 – 10:30</strong> Andrew Kille (NYU)</summary>
  <p><em>Title:</em> QuantumSymbolics: a quantum-focused symbolic interface</p>
  <p><em>Abstract:</em> The quantum software ecosystem is a vast landscape of libraries implementing classical simulation algorithms based on various formalisms of quantum information. Choosing the appropriate formalism when designing quantum algorithms and hardware is highly problem-dependent, therefore an efficient workflow between different simulation backends is valuable. Furthermore, avoiding the peculiarities of individual quantum software libraries prioritizes the key aspects of developing quantum technologies.</p>
  <p>Our approach to these challenges is QuantumSymbolics.jl, a computer algebra package that serves as a symbolic interface to numerical quantum simulation libraries. In this talk, we present features of QuantumSymbolics.jl such as symbolic manipulation capabilities and numerical translations to state-vector simulations, Gaussian quantum information, and Clifford stabilizer circuits. In particular, we emphasize Gabs.jl, a numerical package for simulating a large class of quantum continuous variables known as Gaussian quantum information. Gaussian processes are efficient to simulate on a classical computer, thus serving as a practical tool for developing applications in quantum teleportation, quantum networking, and quantum computation.</p>
</details>

<details>
  <summary><strong>10:30 – 10:45</strong> David Ittah (Xanadu)</summary>
  <p><em>Title:</em> There and back again: jeff bridges Quantum Compilers</p>
  <p><em>Abstract:</em> Existing intermediate exchange formats for quantum programs are either designed for human interfacing with parsing and translation overheads, or are poorly adapted for quantum compilation and high-level, structured program representations. This talk introduces jeff, a simple, hierarchical and graph-based exchange format for quantum compilers. With a similar structure to existing modern compiler IRs, jeff aims to reduce the loss of abstraction when interoperating different tools, while focusing on the most important properties of quantum programs to minimize complexity. Besides facilitating efficient data exchange between compilers, jeff can be used to quickly disseminate novel compilation techniques for integration and testing across a host of tools, regardless of vendor.</p>
</details>

<details>
  <summary><strong>10:45 – 11:00</strong> Stefan Krastanov (UMass)</summary>
  <p><em>Title:</em> Faster-than-Clifford simulations of Bell and GHZ purification circuits and their full-stack optimization</p>
  <p><em>Abstract:</em> Quantum Entanglement is a fundamentally important resource in Quantum Information Science; however, generating it in practice is plagued by noise and decoherence, limiting its utility. Entanglement distillation and forward error correction are the tools we employ to combat this noise, but designing the best distillation and error correction circuits that function well, especially on today's imperfect hardware, is still challenging. Here, we develop a simulation algorithm for distillation circuits of Bell states and GHZ states with gate-simulation complexity of O(1) steps, providing for drastically faster modeling compared to O(n) Clifford simulators or O(2^n) wavefunction simulators over n qubits.</p>
  <p>This new simulator made it possible to not only model but also optimize practically interesting purification circuits. It enabled us to use a simple discrete optimization algorithm to design purification circuits from n raw states to k purified state. The resulting purification circuits are the best-known purification circuits for finite-size noisy hardware and can be fine-tuned for specific hardware error models.</p>
  <p>In implementing diverse quantum operations with the highest fidelity possible, it is crucial to specialize characterization and calibration protocols to the unique properties of both the quantum hardware and its classical control stack. This talk will present a suite of precise calibration protocols, highlighting how their precision is achieved by leveraging the inherent hierarchy of noise sources and control knobs in superconducting qubits. A key focus will be on INSPECT (In-Situ Pulse Envelope Characterization Technique), a novel method for suppressing pulse distortions that is poised to enable various pulse shaping applications.</p>
</details>

▷ **11:00 – 11:30** Panel 1


---

## Session 2: Device-aware error correction
**🕐 13:00 – 14:30 MDT**  
**Chair:** Siddharth Dangwal  

<details>
  <summary><strong>13:00 – 13:15</strong> Malcolm Carroll (IBM)</summary>
  <p><em>Title:</em> Numeric characterization in the low noise regime</p>
  <p><em>Abstract:</em> Quantum error correction strives to achieve a rare event error regime. A practical consequence is that numeric analysis of high performing codes becomes difficult at many operating points of interest. This talk will discuss extensions of importance sampling techniques to obtain better informed numeric characterization of the Gross and double Gross codes at low noise.</p>
</details>

<details>
  <summary><strong>13:15 – 13:30</strong> Victor Zhou (Yale)</summary>
  <p><em>Title:</em> -</p>
  <p><em>Abstract:</em> -</p>
</details>

<details>
  <summary><strong>13:30 – 13:45</strong> Josh Viszlai (UChicago)</summary>
  <p><em>Title:</em> Propagation-Aware Compilation of Stabilizer Circuits</p>
  <p><em>Abstract:</em> Stabilizer circuits connect QEC codes to the device, enabling the detection and correction of errors through measured out syndrome information. While ultimately implemented as physical circuits, stabilizer circuits have challenges that are not addressed by existing circuit optimization tools. Importantly, inside stabilizer circuits themselves errors are expected to occur, and how errors propagate through the circuit directly impacts which errors are detectable and correctable. This is not modeled in NISQ-era tools, which instead optimize for targets such as gate depth or gate count to mitigate the chance that any error occurs. This gap leaves key questions unanswered about the expected real-world effectiveness of QEC codes. We address this gap and present an automated tool for optimizing stabilizer circuits. We evaluate our tool on a suite of QEC codes and demonstrate its ability to iteratively improve stabilizer circuits and recover the performance of hand-designed circuits.</p>
</details>

<details>
  <summary><strong>13:45 – 14:00</strong> Gokul Ravi (UMichigan)</summary>
  <p><em>Title:</em> Lightweight cryogenic pre-decoders for localized quantum error correction.</p>
  <p><em>Abstract:</em> -</p>
</details>

▷ **14:00 – 14:30** Panel 2  

---

## Session 3: Device-aware quantum control
**🕒 15:00 – 16:30 MDT**  
**Chair:** Andy Goldschmidt  

<details>
  <summary><strong>15:00 – 15:15</strong> Max Seifert (Amazon)</summary>
  <p><em>Title:</em> Frequency-noise-insensitive universal control of Kerr-cat qubits</p>
  <p><em>Abstract:</em> In this work we theoretically study the influence of frequency uncertainties on the operation of a Kerr-cat qubit. As the mean photon number increases, Kerr-cat qubits provide an increasing level of protection against phase errors induced by unknown frequency shifts during idling and X rotations. However, realizing rotations about the other principal axes (e.g., Y and Z axes) while preserving robustness is nontrivial. To address this challenge, we propose a universal set of gate schemes which circumvents the tradeoff between protection and controllability in Kerr-cat qubits and retains robustness to unknown frequency shifts to at least first order. We theoretically and numerically analyze the robustness of elementary gates on Kerr-cat qubits, with special focus on gates along nontrivial rotation axes. An appealing application of this qubit design would include tunable superconducting platforms, where the induced protection against frequency noise would allow for a more flexible choice of operating point and thus the potential mitigation of the impact of spurious two-level systems.</p>
</details>

<details>
  <summary><strong>15:15 – 15:30</strong> Sho Uemura (Fermilab)</summary>
  <p><em>Title:</em> QICK: the Quantum Instrumentation Control Kit</p>
  <p><em>Abstract:</em> QICK is an open-source qubit controller that is used by hundreds of users worldwide in academia and industry.</p>
  <p>While QICK's core application is the control and readout of superconducting qubits, the QICK community has grown to include other device architectures such as quantum dots and neutral atoms, and other applications such as quantum sensing and quantum networks. We present an overview of the QICK project and examples of device-specific modules and extensions to the QICK hardware, firmware, and software.</p>
</details>

<details>
  <summary><strong>15:30 – 15:45</strong> Élie Genois (Google)</summary>
  <p><em>Title:</em> Precise calibration protocols for superconducting qubit operations</p>
  <p><em>Abstract:</em> In implementing diverse quantum operations with the highest fidelity possible, it is crucial to specialize characterization and calibration protocols to the unique properties of both the quantum hardware and its classical control stack. This talk will present a suite of precise calibration protocols, highlighting how their precision is achieved by leveraging the inherent hierarchy of noise sources and control knobs in superconducting qubits. A key focus will be on INSPECT (In-Situ Pulse Envelope Characterization Technique), a novel method for suppressing pulse distortions that is poised to enable various pulse shaping applications.</p>
</details>

<details>
  <summary><strong>15:45 – 16:00</strong> Aaron Trowbridge (CMU)</summary>
  <p><em>Title:</em> Quantum control from a robotics perspective</p>
  <p><em>Abstract:</em> -</p>
</details>

▷ **16:00 – 16:30** Panel 3  


---
