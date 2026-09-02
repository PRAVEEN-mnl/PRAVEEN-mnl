# Praveen Kumar

AI Research Engineer | Machine Learning | Data Science  
Zaragoza, Spain | praveenkumarpkrtk@gmail.com | [LinkedIn](https://www.linkedin.com/in/praveen-pkrtk/)

---

## About

I am an AI research engineer with a PhD in Gravitational Wave Astrophysics and industry experience in applied machine learning. I design and build end-to-end ML pipelines, debug complex model behaviour, and work on research problems that have real-world impact.

I have a long-term residency card in Spain (Carta de Larga Duración) and do not need visa sponsorship to work in Spain. Available immediately.

---

## Open Source Work

### PyCBC (gwastro/pycbc)

PyCBC is the core software package used to analyse gravitational wave data from LIGO and Virgo. It was used in the first-ever detection of gravitational waves (GW150914).

During my PhD, I built a KDE-based ranking statistic to improve the detection of binary black hole signals in LIGO-Virgo O3 data. The previous ranking method found
49 signals above IFAR > 0.5 year and p_astro > 0.5. After implementing the KDE-based ranking, this increased to 57 events, a 16% improvement in detection rate.
This work was merged into the production codebase, published in [Physical Review D](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.043036), and the ranking has since been extended to the O4 observing run.

My contributions:

| File | What it does |
|------|-------------|
| [pycbc_template_kde_calc](https://github.com/gwastro/pycbc/blob/master/bin/all_sky_search/pycbc_template_kde_calc) | Calculates adaptive KDE over the gravitational wave template parameter space. Uses k-fold cross-validation to find the best bandwidth and sensitivity parameters. |
| [pycbc_template_kde_max](https://github.com/gwastro/pycbc/blob/master/bin/all_sky_search/pycbc_template_kde_max) | Finds the maximum KDE values across template parameters. |
| [pycbc_plot_kde_vals](https://github.com/gwastro/pycbc/blob/master/bin/all_sky_search/pycbc_plot_kde_vals) | Plots KDE distributions for signals and templates. |
| [stat.py (KDE sections)](https://github.com/gwastro/pycbc/blob/master/pycbc/events/stat.py) | KDE-related classes and functions in the core statistics module. All code related to KDE in this file are written by me. |

What this work involved:

- Adaptive Gaussian KDE with local bandwidth optimisation using the awkde library
- K-fold cross-validation grid search to select optimal hyperparameters
- Rejection sampling to handle large template banks efficiently
- HDF5 data pipelines processing terabyte-scale detector data
- Clean, modular Python code integrated into a major open-source package

---

## Technical Skills

Languages: Python (NumPy, SciPy, Pandas, Matplotlib), C++, MATLAB

Machine Learning: Scikit-learn, TensorFlow, PyTorch (TorchTT), tensor network methods

Statistics: Bayesian Inference, KDE, Hypothesis Testing, A/B Testing, statistical modelling

ML Engineering: Reproducible pipelines, experiment tracking, model evaluation, algorithmic debugging

Data: HDF5, large-scale datasets, distributed computing (Condor, OSG, HPC environments)

Tools: Git, Docker, Linux, Jupyter, LaTeX

---

## Publications

**Direct contributions:**

P. Kumar and T. Dent, Optimized Search for a Binary Black Hole Merger Population in LIGO-Virgo O3 Data, [Physical Review D, 110, 043036 (2024)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.043036)

LVK Collaboration, GWTC-4.0: Methods for Identifying and Characterizing Gravitational-wave Transients, [The Astrophysical Journal Letters (2025)](https://iopscience.iop.org/article/10.3847/2041-8213/ae447b) — wrote the PyCBC pipeline section

K. Pichamani, J. Samuel, P. Kumar, et al., Sunspot drawings at Kodaikanal Observatory: a representative results on hemispheric sunspot numbers and area measurements, [Astrophysics and Space Science (2020) ](https://link.springer.com/article/10.1007/s10509-020-3725-7)

**LVK Collaboration papers (member authorship):**

Listed as a collaboration author on LVK publications during PhD (2020 to 2025). Full list available on request.

---

## Experience

**ML Engineer, Multiverse Computing, Spain** (Jan - Jun 2026)
Built and evaluated quantum-inspired AI models using PyTorch and tensor network methods (TorchTT). Implemented a TN-preconditioner to fix numerical instability at large scales. Extended models from homogeneous to heterogeneous configurations for industrial simulations.

**PhD Researcher, University of Santiago de Compostela, Spain** (2020 to 2025)
Designed ML pipelines for real-time signal classification and ranking on terabytes of streaming detector data. Achieved 10% improvement in detection sensitivity and 30% faster computation. Published in Physical Review D.

**Visiting Researcher, Utrecht University, Netherlands** (Feb - Apr 2024)
Benchmarked signal detection pipelines for next-generation gravitational wave detectors using Bayesian methods.

---

## Looking For

I am looking for roles in ML Engineering, AI Research, or Data Science. I am particularly interested in teams working on LLMs, agentic AI, or applied ML research. No visa sponsorship needed for Spain. Available immediately.

Contact: praveenkumarpkrtk@gmail.com
