# Drug Release Simulation

## Overview
This project simulates and compares drug release kinetics for first-order and zero-order models using Python. It is designed to study the dynamics of drug delivery systems, particularly relevant for microneedle technologies.

## Objectives
- Visualize drug release profiles over time.
- Analyze differences between burst release (first-order) and sustained release (zero-order).

## Models
1. **First-Order Release**: Drug release rate decreases over time.
   - Formula: `C(t) = C0 * e^(-kt)`
2. **Zero-Order Release**: Drug releases at a constant rate.
   - Formula: `C(t) = C0 - kt` (clipped to ensure non-negative values).

## Results
![Release Profiles](release_profiles.png)

- **First-Order Release**: Ideal for rapid drug delivery with an initial burst.
- **Zero-Order Release**: Suitable for sustained, controlled delivery.

## Files
- `drug_release_simulation.py`: Python script for the simulation.
- `release_profiles.png`: Visualization of the release profiles.
- `README.md`: Documentation of the project.

## How to Run
1. Install Python and required libraries:
   ```bash
   pip install numpy matplotlib
   python drug_release_simulation.py

---

### **Step 4: Push Everything to GitHub**
If you’re familiar with GitHub CLI or Git commands, follow these steps:
1. Open a terminal in your project folder.
2. Initialize Git:
   ```bash
   git init
git add .
git commit -m "Initial commit: Drug release simulation"
git remote add origin https://github.com/YOUR_USERNAME/Drug_Release_Simulation.git
git branch -M main
git push -u origin main

