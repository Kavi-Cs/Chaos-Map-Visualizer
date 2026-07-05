# Chas Map Visualizer

A Python-based graphical user interface (GUI) for exploring one-dimensional nonlinear dynamical systems using the **Logistic Map** and **Tent Map**. The application provides interactive visualization tools commonly used in chaos theory and nonlinear dynamics, making it suitable for educational and research purposes.

---

## Features

- Logistic Map simulation
- Tent Map simulation
- Time Series Plot
- Bifurcation Diagram
- Cobweb Diagram
- Poincaré Plot (Return Map)
- Lyapunov Exponent Estimation
- User-friendly GUI built with Tkinter

---

## Mathematical Models

### Logistic Map

The logistic map is defined by

```text
xₙ₊₁ = r × xₙ × (1 − xₙ)
```

where

- **xₙ** : State variable
- **r** : Growth parameter
- **0 ≤ xₙ ≤ 1**
- **0 ≤ r ≤ 4**

---

### Tent Map

The tent map is defined by

```text
           r × xₙ             , if xₙ < 0.5
xₙ₊₁ =
           r × (1 − xₙ)       , if xₙ ≥ 0.5
```

where

- **xₙ** : State variable
- **r** : Control parameter
- **0 ≤ xₙ ≤ 1**
- **0 ≤ r ≤ 2**

---

## Visualization Tools

### Time Series Plot
Displays the evolution of the state variable over successive iterations.

### Bifurcation Diagram
Illustrates how the long-term behavior changes as the control parameter varies.

### Cobweb Diagram
Visualizes the iterative process using the map function and the identity line.

### Poincaré Plot
Displays successive values **(xₙ, xₙ₊₁)** to identify fixed points, periodic orbits, and chaotic behavior.

### Lyapunov Exponent
Estimates the largest Lyapunov exponent to classify the system dynamics.

| Lyapunov Exponent | Interpretation |
|------------------:|---------------|
| λ < 0 | Stable system |
| λ = 0 | Transition (Bifurcation) |
| λ > 0 | Chaotic system |

---

## Requirements

- Python 3.10 or later
- NumPy
- Matplotlib
- Tkinter (included with most Python installations)

Install the required packages:

```bash
pip install numpy matplotlib
```

---

## Installation

Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/Dynamical-Systems-Explorer.git
```

Navigate to the project directory:

```bash
cd Dynamical-Systems-Explorer
```

Run the application:

```bash
python logistic_tent_gui.py
```

---

## Project Structure

```text
Dynamical-Systems-Explorer/
│
├── logistic_tent_gui.py
├── README.md
├── requirements.txt
├── LICENSE
└── screenshots/
    ├── time_series.png
    ├── bifurcation.png
    ├── cobweb.png
    ├── poincare.png
    └── lyapunov.png
```

---

## Screenshots

Add screenshots of your application to the **screenshots/** directory.

Example screenshots:

- Time Series Plot
- Bifurcation Diagram
- Cobweb Diagram
- Poincaré Plot
- Lyapunov Exponent

---

## Applications

This project is useful for:

- Chaos Theory
- Nonlinear Dynamics
- Mathematical Modeling
- Computational Physics
- Scientific Visualization
- Undergraduate and Postgraduate Research
- Educational Demonstrations

---

## Future Improvements

- Animated Cobweb Diagram
- Lyapunov Spectrum vs. Parameter
- Orbit Diagram
- Interactive Parameter Slider
- Export Data to CSV
- Save Figures as PNG/PDF
- Additional Chaotic Maps
  - Hénon Map
  - Ikeda Map
  - Sine Map
  - Circle Map

---

## Author

**Kaveesha Induwara**

Department of Physics

Project: **Computational Physics – Chaos Visualization Using Logistic and Tent Maps**

---

## License

This project is licensed under the **MIT License**.

---

## Acknowledgements

This project was developed as an educational tool for studying nonlinear dynamical systems and chaos theory using Python. It demonstrates classical discrete-time maps and standard visualization techniques widely used in mathematics and physics.
