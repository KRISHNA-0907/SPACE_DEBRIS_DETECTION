# Space Debris Detection & Visualization Tool

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Library](https://img.shields.io/badge/library-Plotly-orange)
![Status](https://img.shields.io/badge/status-prototype-yellow)

## 📖 Overview

This project is a Python-based software prototype developed to address the growing challenge of space debris in Low Earth Orbit (LEO). It automates the detection, parsing, and visualization of orbital debris and active satellites from public Two-Line Element (TLE) data sets. The core output is an interactive 3D scatter plot that provides an intuitive view of the spatial distribution of debris, highlighting collision risks and supporting research into debris mitigation strategies.

## ✨ Features

- **TLE Data Parser:** Reads and parses standard Two-Line Element sets from text files.
- **Orbital Mechanics Calculator:** Extracts key parameters (eccentricity, inclination, mean motion, etc.) and calculates the semi-major axis.
- **3D Coordinate Transformation:** Converts Keplerian orbital elements into 3D Cartesian coordinates (X, Y, Z) for visualization.
- **Interactive 3D Visualization:** Creates an interactive plot using Plotly, featuring:
  - A sphere representing Earth.
  - Data points for debris and active satellites, sized by altitude.
  - Hover tooltips displaying detailed orbital information for each object.
- **Debris Cluster Analysis:** Clearly visualizes debris concentration from specific fragmentation events (e.g., FENGYUN-1C).

## 🛠️ Installation & Usage

### Prerequisites

- Python 3.8+
- `pip` (Python package installer)

### Dependencies

Install the required Python libraries:
```bash
pip install numpy plotly
