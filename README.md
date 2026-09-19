# Messy Mashup – Robust Music Genre Classification

## Overview

*Messy Mashup* is a music genre classification challenge focused on robustness under realistic mixing conditions.

The training data consists of songs from **10 genres**, each separated into four stems:

- drums  
- vocals  
- bass  
- others  

Additionally, random noise samples are provided.

Unlike the clean training tracks, the test set contains **genre-consistent mashups** created by:

- Recombining stems from different songs  
- Applying tempo synchronization  
- Varying instrument balances  
- Adding noise at different intensities  

## Objective

The goal is to build models that:

- Generalize across distribution shifts  
- Accurately predict the genre of noisy mashups  
- Learn robust audio representations  
- Handle tempo variation and environmental noise  

---

# Folder Structure

project-name/

├── notebooks/  
│   ├── milestone-1.ipynb  
│   ├── milestone-2.ipynb  
│   └── final_notebook.ipynb  

├── src/  
│   ├── train.py  
│   ├── inference.py  
│   └── utils.py  

├── reports/  
│   ├── milestone-1-report.pdf  
│   ├── milestone-2-report.pdf  
│   └── final-report.pdf  

├── models/  

├── requirements.txt  

└── README.md
