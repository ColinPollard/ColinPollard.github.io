---
title: "Physical Pong"
classes: wide
excerpt: "Pong, but more physical and needlessly complex."
header:
  teaser: /assets/images/PPKnob.png
sidebar:
  - title: "Category"
    image: /assets/images/PPKnob.png
    image_alt: "logo"
    text: "Physical Design Lab Final Project"
  - title: "Project Members"
    text: "Colin Pollard, Luke Majors, Ian Lavin, McKay Mower."
  - title: "Skills Utilized"
    text: "FPGA, Verilog, CPU Design, Mechanical Design, 3D Printing, MCU"
---

---

**Project Overview**

The Physical Pong project was the final product of the digital circuit design track at the University of Utah. Inspired by the Pong coffee table product, I wanted to recreate the classic Atari game using hardware we designed from the ground up.
The core of the machine is powered by a CR16 processor, designed entirely by our team. Interfaced with rotary encoders, and a UART communication link to a Teensy 4.0, the processor is able to move the paddles and ball through the play area in real time. 

The entirety of the mechanical design, including 3D printed parts and linear rails was designed by myself, while the processor architecture was a collaborative effort of the team. The game logic was programmed by Luke Majors and McKay Mower.

For more technical details, see the final report document below, and the repository of all of the source code at: <https://github.com/ColinPollard/ECE3710>

---

**Video Demonstration**

{% include video id="Y-5tKdzdlXg" provider="youtube" %}

---

**Report**

<embed src="https://colinpollard.github.io/assets/documents/PhysicalPongReport.pdf" type="application/pdf" />

---

**3D Files**

The entirety of the mechanical design was designed in OnShape prior to assembly. This project was a particularly fun design to make as it a lot of design freedom, and many parts that had to mesh together. The files are available at: <https://cad.onshape.com/documents/e912a39233c946f65e0882cb/w/abfa888f53d0ee6276b1eb63/e/f2232cc595704ea3229360c0>

---

**Next Steps**

The project was a great success, especially as a school project. Moving into the future, I would like to port the entire game logic onto the microcontroller to eliminate the need for an expensive FPGA dev kit. I would also like to embed the mechanical design into a coffee table like the original inspiration of the project.

---

**Inspiration**

{% include video id="HCLdnSABfto" provider="youtube" %}

---

**Team Member Roles**

- Colin Pollard: Mechanical design & assembly, microcontroller programming, processor architecture.
- Ian Lavin: Processor architecture, test bench development.
- Luke Majors: Assembler development, processor architecture, game logic.
- McKay Mower: Processor architecture, game logic.
