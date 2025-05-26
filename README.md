# Möbius Strip Modeling in Python

This project models a Möbius strip using parametric equations, and computes:

- ✅ Surface area (via numerical integration)
- ✅ Edge length (via boundary traversal)
- ✅ 3D visualization using Matplotlib

## 📌 Features

- Parametric mesh generation
- Accurate surface and edge computation
- Clean modular Python code
- 3D plot using `matplotlib`

## 📷 Visualization

![Mobius Plot](mobius_plot.png)

## 🧮 Equations Used

```math
x(u,v) = (R + v·cos(u/2))·cos(u)  
y(u,v) = (R + v·cos(u/2))·sin(u)  
z(u,v) = v·sin(u/2)
