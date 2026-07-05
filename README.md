# Chaos-Map-Visualizer

A Python GUI application for exploring one-dimensional nonlinear dynamical systems using the **Logistic Map** and **Tent Map**. The application provides several visualization tools commonly used in chaos theory and nonlinear dynamics.

---

## Features

- Logistic Map
- Tent Map
- Time Series Plot
- Bifurcation Diagram
- Cobweb Diagram
- Poincaré Plot (Return Map)
- Lyapunov Exponent Estimation
- Simple graphical user interface (Tkinter)

---

## Mathematical Models

### Logistic Map

\[
x_{n+1}=rx_n(1-x_n)
\]

where:

- \(x_n\) is the state variable
- \(r\) is the growth parameter
- \(0 \leq x \leq 1\)
- \(0 \leq r \leq 4\)

---

### Tent Map

\[
x_{n+1}=
\begin{cases}
rx_n, & x_n < 0.5 \\
r(1-x_n), & x_n \ge 0.5
\end{cases}
\]

where:

- \(0 \leq r \leq 2\)

---

## Visualizations

### 1. Time Series
Displays the evolution of the state variable over successive iterations.

### 2. Bifurcation Diagram
Shows how the long-term behavior changes as the control parameter varies.

### 3. Cobweb Diagram
Illustrates the iterative process graphically using the map function and the identity line.

### 4. Poincaré Plot
Plots successive values \((x_n, x_{n+1})\) to visualize periodic and chaotic behavior.

### 5. Lyapunov Exponent
Estimates the largest Lyapunov exponent to distinguish stable and chaotic dynamics.

- λ < 0 : Stable
- λ = 0 : Transition
- λ > 0 : Chaotic

---

## Requirements

- Python 3.10 or later
- NumPy
- Matplotlib
- Tkinter (included with most Python installations)

Install dependencies:

```bash
pip install numpy matplotlib
```

---

## Running the Program

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Dynamical-Systems-Explorer.git
```

Move into the project directory:

```bash
cd Dynamical-Systems-Explorer
```

Run the application:

```bash
python logistic_tent_gui.py
```

---

## Project Structure

```
Dynamical-Systems-Explorer/
│
├── logistic_tent_gui.py
├── README.md
├── requirements.txt
└── screenshots/
    ├── time_series.png
    ├── bifurcation.png
    ├── cobweb.png
    ├── poincare.png
    └── lyapunov.png
```

---

## Example GUI

Add screenshots of your application in the **screenshots/** folder.

Example:

- Time Series
- Bifurcation Diagram
- Cobweb Diagram
- Poincaré Plot
- Lyapunov Exponent

---

## Applications

This project can be used for:

- Chaos Theory
- Nonlinear Dynamics
- Mathematical Modeling
- Undergraduate and Postgraduate Projects
- Scientific Visualization
- Educational Demonstrations

---

## Future Improvements

- Animated Cobweb Diagram
- Lyapunov Spectrum
- Orbit Diagram
- Interactive Parameter Slider
- Data Export (CSV)
- Save Figures
- Additional Chaotic Maps (Henon, Ikeda, Sine, Circle)

---

## Author

**Kaveesha**  
Department of Physics  
University Project on Nonlinear Dynamical Systems

---

## License

This project is licensed under the MIT License.
