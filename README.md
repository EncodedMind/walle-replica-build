# WALL-E Replica Build 🛠️🤖

This repository documents my personal build of the [WALL-E Replica Robot](https://wired.chillibasket.com/3d-printed-wall-e/), an open-source robotics project designed by [chillibasket](https://github.com/chillibasket). I built this project in 2019 - 2020, when I was just 14 years old. This was my first robot that inspired me to make my own robot one day. (The original designs, code, and instructions belong to the creator, and this repository serves as a showcase of my assembly process and experience.

---

## 🔍 Overview

The WALL-E Replica Robot is a 3D-printed, microcontroller-powered robotic replica of the beloved WALL-E character. This repository highlights:
- My personal experience building the robot.
- Photos of the final product.
- Troubleshooting and tips I discovered during the process.

---

## 📸 My Build

Here are some images of my completed robot:

![WALL-E Front View](path/to/your/image1.jpg)
![WALL-E Side View](path/to/your/image2.jpg)
![WALL-E Back View](path/to/your/image3.jpg)

---

## 🛠️ What I Did

1. **3D Printing:**
   - Used a [`WANHAO Duplicator i3 Plus`](https://wanhao.store/products/wanhao-i3-plus-mkii) to create the parts based on the provided STL files.
   - Material: `PLA`.

2. **Assembly:**
   - Followed the assembly guide from the original repository.
   - Connected the microcontrollers and wired components as instructed.

3. **Challenges:** \
   Building the WALL-E replica wasn’t without its hurdles. Here are some of the major challenges I encountered and how I overcame them:

   - Battery Size Issues:

      - The battery I found was too large, forcing all the components to be squished together inside the robot. This led to:
      - Multiple jumper wires breaking due to stress.
      - Several GPIO pins on the Arduino being damaged beyond repair.
      - **Solution**: I purchased a new Arduino and made significant improvements:
      - Covered the Arduino and Raspberry Pi with protective cases.
      - Improved cable management by carefully rerouting wires.
      - Drilled a hole in the robot’s body to mount the speaker on the exterior, freeing up internal space.

   - 3D Printing Problems:

      - Poor bed leveling resulted in wasted plastic and time.
      - **Solution**: I re-calibrated my 3D printer, fine-tuning the bed leveling process for better prints.
     
   - Painting Difficulties:

      - The initial spray paint application had uneven coverage and required a second coat.
      - For hard-to-reach spots, I used a marker for finer details.
    
   - Assemblying Problems:

     - Paint inside connection points created tight fits, making assembly difficult.
     - **Solution**: I used a wood rasp-cut file to carefully widen and clean the connections, ensuring components fit properly.

   - Coding Bugs:

      - The robot’s software contained several bugs that were challenging to debug, especially when running on the Raspberry Pi.
      - **Solution**: I dove into Raspberry Pi-specific debugging tools and learned new techniques to fix the issues, which was a valuable learning experience.

4. **Final Testing:**
   - Successfully tested movement, sounds, and other functionalities.

---

## ⚙️ Original Project

For detailed instructions and code, visit the original repository:  
- [WALL-E Replica by chillibasket](https://github.com/chillibasket/walle-replica).
- STL files can be found [here](https://www.thingiverse.com/thing:3703555).

---

## 💡 Tips and Notes

- If you’re building this, ensure you have access to a well-calibrated 3D printer, with proper leveling.
- Use yellow and grey filaments, or white - as I did - and paint using acrylic spray paint.
- Double-check the wiring diagrams before powering on the robot.

---

## 📝 License

This repository is a personal showcase and follows the licensing terms of the [original repository](https://github.com/chillibasket/walle-replica).  
All credit for the design, code, and instructions goes to the [original creator](https://github.com/chillibasket).
