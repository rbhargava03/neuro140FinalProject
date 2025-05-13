# Neuro140FinalProject- Rajan Bhargava

# Orbital Object Classification (TLE‑Only)

**Goal**

* Use just four numbers from Space‑Track Two‑Line Elements (period, inclination, apogee, perigee) to tell **payloads** from **debris**.
* expand on my own limited coding experience through exploration of the machine learning models for use in a personal area of interest (aerospace) 
  
**Folder overview**

* `spaceobjectid_neuralnetwork_.py` – feed‑forward PyTorch model (adapted from our class Assignments 1 & 2), as well as analysis of model evolution and the confusion matrix.
* `spaceobjectid_lrandrf.py` – logistic‑regression & random‑forest baselines with scikit‑learn, confusion matrices, and overall model comparison graph.
* `PayloadDebrisData.csv` – Norad SpaceTrack CSV with payload and debris data downloaded February 25, 2025.

**Code credit**

* Neural‑network script adapted from course starter code (Assignments 1–2).
* Sci-kit learn code adapted to help with Random Forest and Logistic regression implementation
* Everything else done by me.
* Packages used: PyTorch, scikit‑learn.
