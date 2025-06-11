# Fractal Cortex

Fractal Cortex is an open source multidirectional 5-axis FDM slicer.

⚙️ A benchtop 5-axis 3D printer was developed to go along with this slicer. **You can check out the GitHub page for it here**.

<p align="center">
  <img src="./examples/GUI_Prepare_Screenshot.PNG" width="700">
</p>

# Slicer Overview
Fractal Cortex is a multidirectional 5-axis FDM slicer that is backwards compatible with 3-axis slicing. It is organized in a familiar way to popular traditional 3-axis slicers and contains many of the same print settings. This overview will primarily cover what makes Fractal Cortex unique to existing slicer applications.

**What is multidirectional 5-axis slicing?**
Multidirectional 5-axis slicing allows parts to be printed in "chunks", wherein the user may define any number of slicing directions for a given part. This method is not non-planar slicing.

**Features**
- 5-Axis Mode
  - Apply 

- 3-Axis Mode

# Project Motivation
This project was motivated by the **Fractal Robotics** vision: **To accelerate the development of mechanical solutions.** In support of this vision, this project aims to address the gap between the limitations of 3-axis FDM and the inaccessibility of current 5-axis FDM.

**📋Limitations of 3-Axis FDM**
  - Part strength is limited due to the direction of printing
    - Parts often fail when forces are applied parallel to the direction of layer lines
    - Stacking layers in only one direction limits design freedom
  - Overhangs require support structures
    - The process of removing supports often damages or destroys a part
    - Support structures waste material

**🔒Inaccessibility of Existing 5-Axis FDM**
  - No commercially available intuitive slicer applications
    - Non-planar slicing requires significant training on advanced CAM softwares
  - Commercially available 5-Axis 3D printers are huge and expensive

---

# Note From the Author to the Community
Hi, my name is Dan Brogan, and I spent 3 years (2022-2025) bootstrapping a startup called Fractal Robotics while working part time jobs. Over those 3 years, I developed technical acumen in end-to-end robotics product development, improved my communication skills, and learned a great deal about what goes into running a startup. 

My career goal has always been and continues to be **to contribute to society through technology in a way that has a positive impact**. That goal was translated into the vision of Fractal Robotics, which is "to accelerate the development of mechanical solutions".

At this point, I am unable to continue volunteering my full effort into this project. While I won't be stepping back entirely, I have decided the best path for this project is to release both the Fractal Cortex slicer and designs for the Fractal 5 Pro under an open source license so that others can learn from, build upon, and contribute to it. 

Open sourcing this project allows me to fulfill the original vision of Fractal Robotics. By sharing my work, I hope to support researchers, developers, educators, and makers exploring similar ideas.

I'm excited to see where others take this work next.

Feel free to [connect with me](https://www.linkedin.com/in/dan-brogan-442b27128/) on LinkedIn.

# 💻System Requirements
- OS: Windows 10
- Python: 3.10.11
- Python Libraries:
  - glooey 0.3.6
  - numpy 1.26.4
  - numpy-stl 3.1.1
  - pyglet 1.5.28
  - pyOpenGL 3.1.0
  - shapely 2.0.4
  - trimesh 4.3.1

---

# 📝Future Work
- Incorporate support generation into both 3 and 5-axis modes

