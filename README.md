# Stochastic Simulation

This repository contains theoretical insights, implementations, and simulation results related to stochastic processes. The focus is on applying stochastic methods to physical and biological systems using tools from statistical physics, stochastic differential equations, and continuous-time Markov chains.

## 📚 Contents

- Brownian motion simulation using Langevin and Fokker–Planck equations
- Ratchet effect simulations and connection with molecular motors
- Epidemic modeling using continuous-time Markov chains (SI, SIR, SIRD models)
- Analytical and numerical comparison with deterministic models

---

## 🔬 Project 1: Brownian Motion and the Ratchet Effect

**Resumen**  
Se estudia el movimiento browniano mediante la ecuación de Langevin y la ecuación de Fokker-Planck deducida a partir de la ecuación de Chapman-Kolmogorov. Se presenta un algoritmo para resolver ecuaciones diferenciales estocásticas para luego aplicarlo sobre la ecuación de Langevin.

El proceso Wiener es simulado para 1000 partículas donde los resultados están de acuerdo con los obtenidos por Einstein y Langevin al estudiar el movimiento browniano. Luego se simula al aplicar un potencial ratchet a 100 partículas. El comportamiento de 4 partículas brownianas en presencia de un potencial ratchet es simulado para 3 diferentes coeficientes de difusión (1; 0.1; 0.01), luego se enciende y apaga el potencial obteniendo así una corriente neta de partículas denominada efecto ratchet.

Finalmente, el efecto ratchet es extrapolado para explicar aproximadamente el funcionamiento de los motores moleculares.

### 📁 Code Location

> [./brownian-ratchet-simulation/](./brownian-ratchet-simulation/)

### 📈 Results Summary

> _[Add plots or observations here]_  

---

## 🧪 Project 2: Epidemic Spread Modeling with Markov Chains

**Resumen**  
Con la aparición de la pandemia COVID-19, los modelos matemáticos para predecir el comportamiento de la pandemia se han venido desarrollando con el propósito de establecer restricciones para su contención.

En este trabajo se desarrolla el comportamiento en la propagación de una enfermedad a través de simulaciones basadas en la teoría de las cadenas de Markov en tiempo continuo. Para validar los resultados de las simulaciones se comparan con los modelos clásicos ya establecidos basados en ecuaciones diferenciales, y también con los resultados analíticos usando la ecuación de Kolmogorov.

Primero se estudia el proceso de nacimiento-muerte, lo cual es extrapolado a los modelos epidémicos SI y SIR. En la última parte se presenta el modelo SIRD con desfase, aplicado a la tercera ola usando datos epidémicos del distrito de San Juan de Lurigancho, Lima - Perú.

### 📁 Code Location

> [./epidemic-models-markov/](./epidemic-models-markov/)

### 📈 Results Summary

> _[Add plots, tables, or case studies here]_

---

## 🔧 Requirements

```bash
# Example requirements
numpy
scipy
matplotlib
pandas
jupyter
````

> *\[Add full requirements or link to `requirements.txt`]*

---

## 📌 How to Run

```bash
# Example to run simulations
cd brownian-ratchet-simulation
python simulate.py

cd ../epidemic-models-markov
python epidemic_simulation.py
```

> *\[Add usage instructions or demo notebooks here]*

---

## 📖 Theory and Background

> *\[Add background notes or links to your PDFs, notebooks or markdown explanations here]*

---

## 🧠 To-Do / Future Work

* [ ] Improve visualization of ratchet simulations
* [ ] Extend epidemic models to include vaccination or stochastic lockdown policies
* [ ] Add Jupyter notebooks for interactive exploration
* [ ] Integrate with real-time data sources

---

## ✍️ Author

**Angel Chaico**

* [LinkedIn](https://www.linkedin.com/)
* [Personal Website](https://yourwebsite.com/)
* [Email](mailto:your_email@example.com)

---

## 📜 License

> *\[Specify the license: MIT, GPL, etc.]*
