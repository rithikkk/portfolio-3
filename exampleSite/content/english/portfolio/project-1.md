---
title: "Remote Plant Monitoring for MacEwan University"
date: "2022-09-01"
image: "images/portfolio/item1.png"
categories: ["IoT", "Hydroponics", "Cloud", "Android Development"]
description: "An IoT-based remote plant monitoring system for hydroponic gardens at MacEwan University."
draft: false
project_info:
- name: "Client"
  icon: "fas fa-user"
  content: "MacEwan University"
- name: "Project Type"
  icon: "fas fa-seedling"
  content: "Hydroponic Garden Monitoring"
- name: "Technologies"
  icon: "fas fa-cogs"
  content: "Arduino, Java, Android Studio, Arduino Cloud"
- name: "Project Link"
  icon: "fas fa-link"
  content: "https://drive.google.com/file/d/18dxC3tzk1tMHLqODEevuHQkyBSPyT5Jr/view?usp=sharing"
---

### **Overview**

The core objective of this project was the design and implementation of an IoT device that remotely monitors hydroponic gardens at MacEwan University. This device is responsible for capturing and recording vital metrics crucial for the optimal growth of plants. The readings are visualized intuitively and past data is accessible, making growth analysis over time feasible.

### **Objectives**

Given the goal to monitor the hydroponic gardens effectively:
- A microcontroller serves as the core, connected to multiple sensors, which then consolidates data and pushes it to the cloud.
- Key parameters for monitoring include water pH, which directly impacts nutrient absorption, and the electrical conductivity (EC) that indicates dissolved solid levels in the water. These readings, especially in a hydroponic setup, are crucial for the health of the plants.
  
### **Development Environment**

For the software, we used Android Studio, the leading IDE for Android development. The choice of Java (SDK 8) ensured a robust and flexible application development process. This language, combined with its extensive libraries, is optimal for the development of an application like ours. The focus was to ensure modularity for potential scalability while ensuring the presentation of all necessary plant data.

### **Cloud Integration**

Arduino Cloud was the chosen platform for cloud integration due to its seamless compatibility with Arduino hardware. This integration ensures data security using secret keys, facilitating a secure data upload. Arduino's GUI for its cloud service aids manual data management and offers an intuitive platform for hardware data testing, thus simplifying debugging processes.

### **Conclusion**

By leveraging advanced IoT and cloud technologies combined with efficient software development practices, the project successfully provided MacEwan University with a comprehensive solution for monitoring their hydroponic gardens remotely, ensuring optimal growth and health of the plants.
