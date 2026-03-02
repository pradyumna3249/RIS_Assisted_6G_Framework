# RIS-Assisted 6G Wireless Communications: Statistical Framework Implementation

This repository contains the full numerical and statistical reimplementation of the RIS-Assisted 6G Wireless Communication framework in the presence of a direct channel.

The project validates analytical expressions using numerical simulation and demonstrates stability across varying system parameters.

---

## 📌 Overview

The composite channel consists of:

- Direct channel component
- RIS-assisted reflected component
- Statistical modeling under Nakagami-m fading
- Parameter variations for m1, m2 and RIS elements N

Analytical PDFs are validated against Monte Carlo simulations.

---

## 📊 Results

### 🔹 Figure 2: Stable Implementation of RIS-Assisted Composite Channel PDF

<p align="center">
  <img src="results/fig2_composite_pdf.jpeg" width="750"/>
</p>

---

### 🔹 Figure 3: PDF of Envelope Starting from Origin

<p align="center">
  <img src="results/fig3_envelope_pdf.jpeg" width="750"/>
</p>

---

### 🔹 Figure 4: Phase Distribution f_{∠h}(θ)

<p align="center">
  <img src="results/fig4_phase_distribution.jpeg" width="750"/>
</p>

---

## 🧠 Methodology

- Composite channel modeling with RIS + Direct link
- Nakagami-m fading parameters (m1, m2)
- Variation of RIS elements (N = 32, 64)
- Closed-form PDF derivation
- Monte Carlo simulation validation

---

## ▶️ How to Run

Python scripts included:

- figure_2.py
- fig3.python.py
- fig4_a,b.py

Run using:

```bash
python figure_2.py
```

---

## 👨‍🔬 Author

Ogiboyina Jaya Pradyumna Kumar Yadav  
National Institute of Technology Delhi  

Research Area: RIS-Assisted 6G Systems, Statistical Channel Modeling, Digital Twin Integration

---

This repository is intended for academic and research purposes.
