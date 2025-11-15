# Political Tweet Classification Using Model-Based Machine Learning  
**Course:** 42186 – Model-Based Machine Learning (DTU)  
**Group 15**

This repository contains the implementation and analysis for a model-based machine learning project aimed at classifying political tweets from the **2020 U.S. Presidential Election** into *Democratic* or *Republican* classes.  
The project compares two probabilistic models:

- **Bayesian Logistic Regression (BLR)** — a simple, interpretable baseline  
- **Bayesian Hierarchical Model (BHM)** — a custom, more expressive model integrating multiple probabilistic components  

All modeling, inference, evaluation, visualization, and experimentation are performed in the notebook **`Final_notebook_group15.ipynb`**.  
Full methodology and discussion are included in **`Model_based_ML.pdf`**.

---

## Project Context

**Course:** 42186 – Model-Based Machine Learning  
**Institution:** Technical University of Denmark (DTU)  
**Academic Period:** Spring 2025  
**Group members:**  
- Mads Yar — s193992  
- Salik Muneeb — s215133  
- Ignacio Ripoll — s242875  
- Carlos Fernández Liger — s243308  

The project follows the model-driven framework taught in the course, where probabilistic modeling, interpretability, and uncertainty quantification are central design principles.

The chosen task is:

> **Classifying political affiliation (Democrat vs. Republican) from tweet text during the 2020 U.S. election.**

The dataset is obtained from Kaggle and contains **1.7M+ tweets**, later cleaned and balanced to ~1.2M tweets for training.
