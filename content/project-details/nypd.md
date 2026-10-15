+++
draft = false
title = "Project NYPD Enforcement Gap"
description = "Compared linear, tree-based, and neural network models to examine what predicts physical force during NYPD stops."
+++

**Tools:** Python (scikit-learn, TensorFlow, Pandas)  
**Course:** Machine Learning for Public Policy  
**Links:** [Report](https://drive.google.com/file/d/1thRrmlFTj4hrptw08muKC_4v_jTs68zo/view?usp=sharing), [GitHub Repository](https://github.com/amylin1249/nypd-enforcement-gap)

### Overview
Working in a team of three, we used machine learning to examine which factors predict whether New York Police Department (NYPD) officers use physical force during stop, question, and frisk encounters. Using NYPD data from 2025, we modeled force as a function of demographic and situational factors, and compared the performance of a linear model, tree-based models, and a neural network. I developed the data cleaning pipeline that underlies all three models, as well as the neural network. By identifying which demographic and situational factors are associated with escalation to use of force, this analysis can help oversight bodies and advocates increase transparency around the NYPD's physical encounters with civilians and focus accountability efforts where they are most needed.

### My Contributions
#### Data Preparation
* **Reproducible Cleaning Pipeline:** Consolidated the team's cleaning steps into a single pipeline that standardizes null values, bins ages, and sets baseline categories for race comparisons.
* **Leakage Prevention:** Identified that the "frisked," "searched," and "arrested" flags were near-proxies for the outcome, and subsequently removed them to prevent data leakage and ensure the models' results were valid.

#### Modeling
* **Neural Network:** Developed the Keras network, tuned through a scikit-learn pipeline with regularization and class weighting to handle the imbalanced outcome, achieving the highest recall of all our models.
* **Model Comparison & Visualization:** Produced the evaluation and feature-importance plots used to compare models, and wrote major sections of the final report.
