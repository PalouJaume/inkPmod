# __inkPmod__

<p align=center>
    <img width="108" height="108" src="./Documentation/Images/inkPmod.svg">
</p>

# Welcome! 👋

Hi there! This repo documents a personal project where I extended the functionality of the Pynq Z2 board by adding support for an E-Ink display from Adafruit. Since none of the available Pmod modules quite met my needs, I decided to roll up my sleeves and design a custom Pmod board using KiCad.

To make the integration seamless, I also created a custom IP block to handle communication between the Pynq board and the E-Ink display. On top of that, I developed a simple C API, allowing control of the display in both bare-metal applications and on a lightweight Linux distribution.

## 🎯 Objective 

Aside from playing around with E-Ink displays and FPC connectors, this project is also a chance for me to sharpen my PCB design skills and learn a few new tricks along the way. Here's what I'm focusing on:

- Deepening my understanding of PCB layout best practices
- Exploring practical applications of stitching vias
- Working through hands-on design challenges with a real-world component

### 📚 Learning Resources

To guide the process, I'm referencing a few great resources:

- 📘 [PCB Design Tutorial (Stanford)](https://www.scs.stanford.edu/~zyedidia/docs/pcb/pcb_tutorial.pdf)
- 📺 [2-Layer PCB Design Tips – Phil's Lab #137 (YouTube)](https://www.youtube.com/watch?v=M6_an34wQJk&t=85s)
- 🧠 [Everything You Need to Know About Stitching Vias (Altium)](https://resources.altium.com/p/everything-you-need-know-about-stitching-vias)

## 🔧 Hardware Design & Schematics

The core of this project revolves around the 2.13" Flexible Monochrome E-Ink Display from Adafruit:

[2.13" Flexible eInk Display – 212x104 Monochrome](https://www.adafruit.com/product/4243)

To design the custom Pmod, I based my schematics on the reference circuit provided in the official datasheet:

📄 [Display Datasheet (PDF)](https://cdn-shop.adafruit.com/product-files/4243/4243_datahseet_GDEW0213I5F_V1.1_Specification__1_.pdf)

Before diving into the layout, I identified the key components and signal requirements based on this reference. My focus was on building a compact and reliable interface that would be easy to integrate with the Pynq Z2.

## 🛠️ Features (WIP)
This project is still a work in progress, but here’s a sneak peek at what I’ve implemented or planned:

- 🔄 Custom Pmod-compatible board in KiCad

- 🔜 Basic working schematic & layout

- 🔜 Photos of the board being tested

- 🔜 Custom IP block for display communication

- 🔜 C API for easy control (bare-metal & Linux)

## 💬 Why I'm Sharing This
I’m sharing this not just to document my own journey, but in hopes it might help others who are exploring similar ideas—or inspire someone to try a custom Pmod project of their own!

If you have feedback, suggestions, or just want to geek out about FPC connectors and Pynq projects, feel free to open an issue or drop a message. 😊


