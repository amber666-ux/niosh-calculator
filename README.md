# NIOSH Lifting Equation Calculator (MIL-STD-1472H)


👉 **[Click Here for Live Demo](https://amber666-ux.github.io/niosh-calculator/)**

---

## Project Overview
This tool was developed to simplify and automate the ergonomic risk assessment of lifting tasks. It calculates the **Recommended Weight Limit (WL)** and determines whether a lifting task is safe ("Yes" or "No") based on user-provided physical measurements.

## Key Features
- **Strict Compliance:** Incorporates all multiplier formulas, look-up tables (Frequency & Coupling), and mathematical capping (limits multipliers to $\le 1.0$) as defined by the standard.
- **Dynamic Session Records:** Users can continuously evaluate multiple working postures, and the tool will append the results dynamically into an interactive table.
- **Export to Excel:** Integrated with `SheetJS` to allow users to export all session records into an `.xlsx` file with a single click.

---


## How to Use
1. Open the [Web Calculator](https://amber666-ux.github.io/niosh-calculator/).
2. Fill in the required physical parameters (e.g., Horizontal Distance, Vertical Height, Angle, Frequency).
3. Click the **"▶ Run / Add to Record"** button. The calculated limit and decision will instantly appear in the right-hand table.
4. Repeat for different tasks or postures.
5. Click **"📥 Export Excel"** to download your assessment report.

---

## Note on Images
The diagrams used in the calculator for `Figure 1: Task Variables` and `Figure 2: Asymmetry Angle` are sourced directly from the ergonomic standards guidelines for reference purposes (MIL-STD-1472H).
