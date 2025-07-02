# Estimating Organism Abundance from eDNA Haplotype Frequencies

Welcome! This repository contains code and simulations associated with the manuscript:

**"Estimating Organism Abundance Using Within-Sample Haplotype Frequencies of eDNA Data"**  
*Pedro F. P. Brandão-Dias, Gledis Guri, Megan Shaffer, Elizabeth A. Allan, and Ryan P. Kelly*  

This work presents a statistical framework for estimating the number of individual contributors (N) 
to an environmental DNA (eDNA) sample based solely on within-sample haplotype frequencies. 
This repository includes simulations, estimators, and walk-throughs that support the methods described in the manuscript.

---

## Repository Contents

- **`Estimatin_from_frequency.qmd`**  
  Demonstrates the **closed-form Maximum Likelihood Estimator** based on the deviation between observed haplotype frequencies and population-level expectations.
  It aso includes the functions used to simulate eDNA data used in the main manuscript.

- **`estimating_pi_LOO.qmd`**  
  Implements the **Leave-One-Out (LOO) estimator** to derive population-level haplotype frequencies from a set of samples, without requiring reference tissue datasets.
  Used to avoid circularity when estimating N from observed data.

---

Feel free to explore, adapt, or reproduce any part of the code in this repository.  
For questions or feedback, please contact: **Pedro Brandão-Dias** – pedrobdfp@gmail.com
