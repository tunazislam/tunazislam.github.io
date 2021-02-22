---
<!-- layout: archive -->
permalink: /projects/
author_profile: true
---

M.Sc. Projects:
======

**Genomics and Genome Assembly:**
Developed computational method for improved region-specific assembly of single-copy diploid DNA into adjacent DNA including inaccessible subtelomere segmental duplication regions.

Tools: Python, Shell Scripts, BLAT, 10X Genomics Supernova (De Novo Assembler), BLAST, QUAST, BWA, SAMtools. 

**Protein Secondary Structure:**
Twist analysis of β-strands from atomic structures and 3D images of a protein.

Tools: Python, UCSF Chimera

**High-Performance Computing:**
Developed parallel algorithm for particle deposition in grid according to Particle-In-Cell (PIC) scheme using GPU. In this project, both
sequential code and parallel code (using atomic operation) were implemented for particle deposition. The main bottleneck of the parallel
implementation was to use of atomic instructions which were particularly slow. To achieve more speed up, the parallel PIC simulation code using shared memory was implemented. 

Tools: GPU, CUDA C/C++   

Undergraduate Projects:
======
**Computer Graphics Project:**

1) London Tower Bridge

This project covers a mega structure modeling with walking camera. External structure of the bridge was maintained as similar as the original one. Environments like roads, river, ship etc. were added to make the model more realistic. OpenGL lighting was added and the lighting parameters were adjusted to create day-night views. Textures were added using Loadbitmap to make the model more closer to the original structure. Many additional features like snowfall environment, fireworks etc were attached. 

Tools: Open GL, C++

2) Scene Graph

This project was intended to model a Human from head to toe using a complex tree-structure implementing a two person interaction like – two persons playing football (not the full game, just some moves like- Penalty Shootout)

Tools: OpenGL, C++   

**Software Project:**

1) Chess

In this game 2 players could play chess using both mouse and keyboard as well as a timer was implemented to keep track the time of players spent to chose any move.

Tools: C, iGraphics Library

2) Hospital Management 

An automated system of Health and Hope Hospital was proposed in this project. Detailed system analysis and design was performed through requirement analysis, requirement modeling, use case analysis, collaboration diagram, class diagram and E-R diagram and following other subsequent steps. The main features were patient database, prescription history, pharmacy management, generation of lab reports, billing etc.

Tools: ASP.NET, C#, Oracle Database  

3) CSE Lab Management 

This  project  provided  a  complete  internet  based  solution  to  CSE  Lab Problems. Users could easily report problems and prioritized them which were automatically sorted, scheduled and managed for a better monitoring purpose. It kept track of the whole process to troubleshooting and trouble reporting, ensuring credentials of the troubleshooter. Then I extended this project by keeping database for Inventory Management and dealing with the challenge for corruption free Tendering System. 

Tools: PHP with CodeIgniter Framework, MySQL Database (use MVC, Design Pattern)

4) K-map Solver

It solved K-Map upto 4 bit and gave result in both SOP and POS format.

Tools: Java

5) Simple Robot with E-puck (Webots)

An E-puck robot was programmed with Webots Simulation software to move and detect obstacles and sounds.

**Hardware Project:**

1) Blind's Eyes

Hardware implementation of Blind's eyes using Sonar Sensor that calculate distances between blind people and obstacles. After completing the measurement speaker tells the distance and blind people get the idea during walking.

2) 4 Bit Computer

A 4 bit Computer which could support 29 instructions and 2 stage pipe lining having maximum Clock Per Instruction (CPI) 2, was designed and simulated. MIPS architectural design was followed and MSI chips were used . An Arithmetic Logic Unit (ALU) and a Modified Booth Multiplier were implemented separately earlier as part of the project.

3) Micro-Controller based Bit Manipulation

Three 7-segment displays and 5 push buttons were used. Input was 8-bit number in memory (initially 00000000). If the first button was pressed it would append a 0 in LSB and MSB would be erased. Similarly if second button was pressed it would append a 1 in LSB and MSB would be erased. If the third button was pressed the new bit would be added from right instead of left, pressing it again would append from left. Every time after appending, the display was updated. Pressing 4th button it would toggle between Hex display and Decimal display. Pressing 5th button would toggle between signed and unsigned status. If the status was unsigned the 8-bit number was considered as unsigned and same for signed. Another display was kept to show negative sign when it was required.Also another button was kept to display the BCD value of the given 8-bit binary number. 
