# About the Workshop

## Organizers

- Andy J. Goldschmidt, Siddharth Dangwal, and Tina Oberoi (University of Chicago)
- Stefanie Guenther (Lawrence Livermore National Lab)
- Gokul Subramanian Ravi (University of Michigan)

## Abstract

There are many proposed hardware implementations for quantum computing. Each is marked by technical challenges and physical limitations. In order to optimize hardware performance, it is critical to consider both the abstract device model and its particular architecture, noise, and error characteristics. This workshop specifically focuses on the design of device-aware quantum software, and the benefits of specialization. It is divided into three focus areas across different layers of the quantum computing stack: control and calibration, noisy classical simulation, and device-aware error correction.

-  Quantum control can be used to synthesize unique hardware primitives and mitigate device-specific errors, but efficient calibration using feedback is critical for success. This focus area emphasizes device-aware machine learning strategies for quantum control and calibration.
- Classical simulation of quantum devices is necessary for studying control, circuit validation, and architecture design. Whether simulating state vectors or logical circuits, this focus area discusses important advances in scalable, noise-aware versions of classical simulators.
- Error rates of quantum hardware currently operate at a juncture where low-distance error correction is implementable. Pushing the frontier requires consideration of all device irregularities in the design of quantum error correcting codes and decoders. In this focus area, device-aware error correcting codes and decoders are discussed. 

In each focus area, four invited speakers will give research talks, then join together for a panel. By concentrating on the way developers of device-aware quantum software work together with hardware experts, this workshop provides opportunities for co-design and cross-layer optimization that can push forward the capabilities of today’s quantum hardware.

## Workshop objectives
The objective of this workshop is to establish a network of developers of device-aware quantum software. Current hardware operates at a threshold where critical improvements can be made by using quantum software specialized on hardware-specific feedback. The objective of this workshop is to encourage conversations between hardware and software experts in order to discover co-design opportunities. It will showcase examples of how software developers have benefited by reaching out to experimentalists in order to incorporate their specialized knowledge. This workshop will especially focus on fostering industry and academic connections. In addition, the workshop will provide opportunities for software developers across layers of the quantum computing software stack to network and share ideas. By exposing developers to different areas and ideas, the workshop will help bridge the gaps between layers and provide educational opportunities.

## Workshop relevance

The need to specialize quantum software for specific hardware characteristics is essential for optimizing the performance of current quantum hardware. Device models, noise models, and feedback are the common tools for achieving specialization, but the utilization of these tools can differ depending on where the incorporating software sits in the quantum computing stack. This workshop will be broadly relevant, helping discover points of commonality and difference in what device information is available and how it can be leveraged to improve hardware performance. In the following, we outline the specific ways we expect this workshop to help developers of quantum software optimize their work for quantum hardware.

### Control and Calibration
The ability to design high-fidelity pulses that implement hardware primitives is fundamental to quantum computers. Good pulse design involves a careful interplay between characterization, control, and calibration. Many control examples, from analytic schemes to quantum optimal control, have shown the possibility of highly accurate quantum gates and subroutines for many systems, and yet control needs differ widely across the physical platform selected for the quantum computer. Moreover, scalable calibration is an equally necessary part of any operation's practical viability. This workshop will highlight device-aware control and calibration schemes that yield uncomplicated pulses that can be efficiently calibrated. 

### Classical simulation
Simulation of quantum devices is essential for the validation and design of quantum operations, architectures, and algorithms. Tools like state-vector simulators and efficient Clifford or Gaussian circuit simulators are becoming more efficient, enabling simulation at larger and larger scales by combining better methods and better usage of classical resources. Many of the simulation tools are excellent because they are general purpose; in contrast, this workshop will focus on simulators that re-introduce hardware-specific noise and errors, or simulators that are adapted for a specific architecture or quantum computing platform. This focus on device-aware simulators over general purpose advances in simulation will offer a unique perspective on this essential area.

### Error correction
This workshop will study device-aware approaches for enhancing error correction. This is critical for a field that is just starting to reach system sizes and control capabilities where experimental studies of quantum error correction are possible. This will be relevant to researchers looking for examples of how this type of specialized research has been done successfully, and for industry looking for ways they can partner with researchers to get the most out of their current devices.

## Anticipated outcomes

First, we expect that this workshop's focus on device-aware quantum software will make it broadly relevant to industry and academic scientists and engineers. This is a key sense of purpose that this workshop inherits from WKS05 (2023) and WKS33 (2024), which are past workshops brought by members of this same organizing team. We have found that the networking aspect of this workshop is especially effective due to the panel format, as panels kick off conversations that carry over to breaks; ideas presented during the workshop and further discussed in panels and breaks have grown into multiple successful collaborations. Another intent of this workshop is to connect researchers that specialize in specific areas of the quantum stack or specific hardware platforms with methods from other communities. As quantum systems continue to grow in size and complexity, it is imperative that we continue to improve techniques that can leverage our increasingly specialized knowledge of these systems. This workshop will allow for important in-person conversations between communities, allowing for the strengths and weaknesses of different approaches to be explored and new perspectives to be brought forth.

## Workshop format
We will stick to the same format as  WKS05 (2023) and WKS33 (2024). It has proven to be very effective and received a lot of positive feedback. The workshop will consist of three 90-minute sessions, with each session consisting of four 17-minute talks (15-minute presentation + 2 minutes for questions), followed by 20 minutes for open panel discussions guided by the workshop organizers and in conjunction with workshop participants. In each session, the four presentations introduce the main concepts and problems that can then be discussed together in more detail during the following discussion. This allows each attendee to familiarize themselves with the session subject first and then contribute to the discussion. This year, there are two notable differences in format. First, we have created a program which is more explicit about the division between each session. It now includes predetermined focus areas. Second, our workshop scope has grown, in order to match the growing reach of the discussions among our participants. 

## Workshop target audience
The workshop will be of interest to a wide audience. Researchers in physics, control engineering, applied mathematics, computer architecture, and more will be invited to speak. We expect a similar diversity amongst our attendees because the work being discussed exists at the interface between software and hardware. Participants will be encouraged to discuss specific details of their work, which is essential to device-aware software development. From these discussions, we expect that the abstractions and general lessons to be taken from this workshop will be broadly applicable to our community, spanning scientists at national labs, academics, industry professionals, and the open-source software community.


## Organizer Biographies

[Andy J. Goldschmidt](https://www.linkedin.com/in/andy-goldschmidt) is an IC Postdoctoral Research Fellow studying novel control and readout schemes for gate-based quantum computing at the University of Chicago, working with Fred Chong. Andy completed his Ph.D. in Physics in 2022 at the University of Washington in Seattle; Andy's thesis focused on physics-informed machine learning and control of dynamical systems. Andy has previously organized quantum workshops at SIAM CSE, IEEE QCE, and JuliaCon.

[Siddharth Dangwal](https://www.linkedin.com/in/siddharth-dangwal-2b16ab153/) is a fourth year PhD student at UChicago working with Fred Chong. He is broadly interested in software and architecture for error correction and error mitigation. He received his bachelor's degree in Electrical Engineering from IIT Delhi. He has previously interned at IBM Quantum, and his work has been published in ISCA, ASPLOS, MICRO, and HPCA

[Stefanie Guenther](https://www.linkedin.com/in/stefanie-guenther) is a research staff member at Lawrence Livermore National Laboratory (LLNL) focusing on quantum dynamical learning and quantum optimal control. She received her PhD in Applied Mathematics in 2017 at RWTH Aachen University, Germany, before joining LLNL under the Sidney Fernbach Fellowship. 

[Tina Oberoi](https://www.linkedin.com/in/oberoitina/) is a first year PhD student in Computer Science at University of Chicago under the guidance of Fred Chong. She received her master’s in computer science from University of Chicago and her undergrad degree from Indian Institute of Technology Roorkee, India. Her research interests include quantum simulations and methods to improve the performance of quantum error correction on real quantum devices.

[Gokul Subramanian Ravi](https://gsravi.engin.umich.edu/) is an Assistant Professor in the Computer Science and Engineering Department at the University of Michigan. His group's research focuses on hybrid quantum-classical computing systems.