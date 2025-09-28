# Solar Tracker Material Calculator
550 MW Photovoltaic Park – Ptolemaida, Greece
Technology Provider: Nextracker Inc. NX Horizon 2.4 Solar Tracker

_A Tkinter-based desktop tool to calculate required materials for solar tracker projects._

##  Overview
This project is a **Photovoltaic Tracker Material Calculator** built in **Python with Tkinter GUI**.  
It allows users to input the number of solar trackers of various types (e.g., `104_EXT`, `78_INT`, `52_EDGE`,`26_HYBRID` etc.), and it automatically calculates the **total materials required** (bolts, torque tubes, rails, piers, etc.).
![Materials_calculator](https://github.com/user-attachments/assets/8764d222-d3e4-4bb3-851e-aeaa6db0eb18)

The tool can also link to **reference images** of parts for easier identification.

![reference_img](https://github.com/user-attachments/assets/6c88aa08-fef8-41e1-9d7b-d533d9955053)

##  Features
- Simple **Tkinter GUI** interface.
- Enter quantities for multiple tracker types.
- Automatically calculates **total Bill of Materials (BOM)**.
- View results in a **sortable table** with item numbers, names, and quantities.
- **Double-click** an item to open its image (if available).
- Works both as `.py` script and packaged `.exe`. 


## ⚡ Requirements
Make sure you have **Python 3.11+** installed.  
Install the following dependencies:

```bash
pip install pillow

Built-in libraries used:

tkinter
ttk (from tkinter)
webbrowser
os
sys
messagebox (from tkinter)

## Project Structure

  tracker_data.py         # Main program
  solar_img/              # Folder containing item images (e.g., 24498.jpg, 52109.jpg...)
  README.md               # Documentation
## How to Run
Clone the repository: and run
python tracker_data.py

or

You can just run the .exe file without even having python installed!!

## Notes
This version is designed for the Ptolemaida 550MW PV Project.

Supports various tracker configurations (EXT, EDGE, INT, HYB) across multiple sizes (104, 78, 52, 26).

Extendable: you can add more trackers, materials, and images by editing tracker_data.py.

## Author

HaRiZ0s
Passionate about renewable energy, automation, and data-driven tools.
