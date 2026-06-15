# Building-AutoCAD

This repository contains the AutoCAD project files for a comprehensive 6-floor building design. This project was developed as part of the CSE200 coursework.

## Project Details

The building features a sophisticated architectural design with the following key characteristics:
- **6-Floor Structure**: A multi-story residential building.
- **Symmetric Cross-Shaped Layout**: Provides optimal space utilization and aesthetic appeal.
- **Unit Distribution**: Four main apartment units per floor, maximizing natural light and ventilation for each unit.
- **Centralized Circulation**: A central staircase (and potential elevator core) serving all units efficiently.
- **Detailed 2D & 3D Views**: 
  - The 2D floor plans include detailed structural walls and door swings.
  - The 3D views showcase both the internal structural framework and the fully roofed exterior, complete with balconies.

## 3D View

<img width="1663" height="783" alt="3D_view" src="https://github.com/user-attachments/assets/1e01ee0d-4213-47dd-89f9-c7803375bbdc" />

## Repository Contents

- `Building Project Tashfin.dwg`: The primary AutoCAD drawing file containing the 2D and 3D models.
- `convert_dwg.py`: A Python script utilizing the `aspose-cad` library, designed to automate the conversion of the `.dwg` file into a PDF format for easier viewing without AutoCAD.

## Viewing the Project

If you do not have AutoCAD installed, you can view the `.dwg` file using one of the following methods:
1. **Online Viewer (Recommended)**: Upload the `.dwg` file to the free [Autodesk Viewer](https://viewer.autodesk.com/) to interactively explore the 2D plans and 3D models in your web browser.
2. **Python Conversion**: If you have Python and `pip` installed, you can run the provided `convert_dwg.py` script to generate a PDF (requires installing dependencies via `pip install aspose-cad`).

## Author

- **Tashfin** - [tashfin5](https://github.com/tashfin5)
