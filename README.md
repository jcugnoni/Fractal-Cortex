# Fractal Cortex

Fractal Cortex is an open source multidirectional 5-axis FDM slicer.

⚙️ A benchtop 5-axis 3D printer was developed to go along with this slicer. **You can check out the GitHub page for it here**.

<p align="center">
  <img src="./examples/GUI_Prepare_Screenshot.PNG" width="700">
</p>

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
Hi, my name is Dan Brogan, and I am the founder of a startup called Fractal Robotics. I created the Fractal Cortex slicer as a product of Fractal Robotics to go along with the Fractal 5 Pro, which is a multidirectional 5-axis 3D printer I designed. My background is Mechanical and Astronautical Engineering, so this project forced me to teach myself how to create a software application from scratch. After 3 years of dedication to this project, I have decided to release both the Fractal Cortex slicer and designs for the Fractal 5 Pro under an open source license so that others can learn from, build upon, and contribute to it.

Open sourcing this project allows me to fulfill my original goal: to accelerate the development of mechanical solutions in a way that benefits the broader community. By sharing my work, I hope to support researchers, developers, educators, and makers exploring similar ideas and to give others a clear window into the engineering and thought process behind the slicer.

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

