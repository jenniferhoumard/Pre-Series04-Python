# Pre-Series 04 – Python

This repository contains the work for the **Pre-Series 04 Python assignment**.

The project focuses on generating a known multidimensional signal, estimating its time derivative, calculating tangential speed, and visualizing the results.

## Assignment Sections

### 1. Generate a Known Signal
- Create a 3D sinusoidal signal.
- Store the `x`, `y`, and `z` coordinates in a NumPy array.
- Visualize the signal in 2D and 3D.

### 2. Estimate the Time Derivative
- Derive the mathematical derivative of the signal.
- Implement the **forward difference** method.
- Implement the **central difference** method.
- Compare the numerical derivatives with the analytical derivative.

### 3. Calculate Tangential Speed
- Explain the difference between tangential velocity and tangential speed.
- Calculate tangential speed from the velocity components.
- Create a function that works with multidimensional signals.
- Test the function using 1D, 2D, 3D, and nD signals.

### 4. Interactive Visualization
- Create an interactive visualization using **Plotly**.
- Display the movement signal and calculated results interactively.

## Main Python Libraries

- `NumPy` – numerical calculations and array manipulation
- `Matplotlib` – signal visualization
- `Plotly` – interactive visualization

## Repository Structure

```text
Pre-Series04-Python/
│
├── sections/
│   ├── 01_generate_known_signal.qmd
│   ├── 02_time_derivative.qmd
│   ├── 03_tangential_speed.qmd
│   └── 04_interactive_plot.qmd
│
├── README.md
└── ...