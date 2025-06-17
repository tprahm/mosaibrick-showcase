# mosaibrick-showcase

# Mosaibrick: Algorithmic LEGO Art Generation Platform

![Project Status: In Progress](https://img.shields.io/badge/status-in%20progress-yellow)
![Language: Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Framework: FastAPI](https://img.shields.io/badge/framework-FastAPI-green)
![Deployment: AWS & Heroku](https://img.shields.io/badge/deployment-AWS%20|%20Heroku-blueviolet)

[cite_start]Mosaibrick is a sophisticated backend system that transforms digital images into custom, buildable LEGO mosaics by generating cost-optimized parts lists, 3D models, and step-by-step PDF building instructions. 

---

## Photorealistic Render Gallery

Here are some examples of mosaics rendered through the automated pipeline.

*(Replace these with links to your actual render images in this repository)*

<p align="center">
  <img src="images/YOUR_RENDER_1.png" width="400" alt="Example Render 1">
  <img src="images/YOUR_RENDER_2.png" width="400" alt="Example Render 2">
</p>

---

## Core Features

* [cite_start]**Custom Optimization Engine:** A multi-objective optimization engine for brick placement, balancing cost and piece variety. 
* [cite_start]**Advanced Image Processing:** A pipeline using OpenCV and computer vision algorithms for pixelation, color mapping, and region detection. 
* [cite_start]**Automated 3D Model Generation:** Programmatically generates multi-part 3D models in LDR/MPD format. 
* [cite_start]**Automated PDF Instructions:** Integrates with LPub3D to automatically produce multi-page, professional-quality building instruction manuals. 
* [cite_start]**Data-Driven Inventory:** Supports integration with LEGO Pick-a-Brick and other sources for real-time inventory and pricing data. 

---

## Technical Architecture

The system is built on a high-performance Python backend designed for complex data processing and automation.

### High-Level Data Flow

```
Input Image → Image Processing Pipeline → Optimization Engine → 3D Model Generation → Output Pipelines (PDF/Render/Parts List)
```
[cite_start][cite: 1]

### Key Technologies

| Category                      | Technologies                                                                                             |
| ----------------------------- | -------------------------------------------------------------------------------------------------------- |
| **Backend Framework** | [cite_start]FastAPI, Uvicorn                                                                                    |
| **Data & Optimization** | [cite_start]Pandas, NumPy, SciPy, Custom Optimization Algorithms                                              |
| **Image Processing & Vision** | [cite_start]OpenCV, Pillow, Matplotlib, LAB Color Space Conversions                                           |
| **3D Modeling & Automation** | [cite_start]LDraw Integration, LPub3D Service Integration, Blender API (`bpy`)                            |
| **Deployment & Infrastructure** | [cite_start]Heroku, AWS EC2, AWS S3                                                                             |

---

## Project Status

* ✅ **Backend:** Complete. The core logic, optimization engine, and all output automation pipelines are fully functional.
* 👨‍💻 **Frontend:** Under Active Development.
