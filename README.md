# Petitjean Index Calculator

A Python implementation for calculating the **Petitjean Index**, a topological descriptor widely used in cheminformatics to characterize molecular shape.  

This project was developed as part of a coding assignment.

---

## 📖 What is the Petitjean Index?
The **Petitjean Index (I)** is defined as:
I = (D - R) / R

Where:
- **D** = graph diameter (longest shortest path in the molecular graph)  
- **R** = graph radius (minimum eccentricity among all vertices)  

It quantifies the ratio of molecular spread by comparing maximum and minimum distances in a graph.

---

## 🚀 Features
- Parses molecular structures from `.mol` and '.sdf' files  
- Constructs molecular graphs using **NetworkX**  
- Computes:
  - Shortest paths  
  - Node eccentricities  
  - Graph radius & diameter  
- Calculates the **Petitjean Index**

---

## 📦 Installation
Clone this repository and install required dependencies:

```bash
git clone https://github.com/PartOfDeasMind/PetitJean-Index.git
cd PetitJean-Index
pip install -r requirements.txt
```
