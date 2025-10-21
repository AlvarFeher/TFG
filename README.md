# Photon Energy Estimation with the Electromagnetic Calorimeter of LHCb
This repository contains the source code, data preprocessing pipeline, and machine learning models developed as part of the Bachelor's Thesis **“Photon Energy Estimation with the Electromagnetic Calorimeter of LHCb”** by Álvaro Feher Argullós (La Salle - Universitat Ramon Llull, 2025).
The project explores the use of machine learning and graph neural networks (GNNs) for photon energy reconstruction in the Electromagnetic Calorimeter (ECAL) of the LHCb detector at CERN.
## 🧠 Abstract
Photon energy reconstruction is a key challenge in high-energy physics. Traditional reconstruction algorithms, such as the Cellular Automaton used in previous LHCb runs, face limitations when handling overlapping showers and complex high-luminosity environments.
This work investigates several machine learning–based approaches — including XGBoost, Multilayer Perceptrons (MLP), and Graph Neural Networks (GNNs) — to estimate photon energy from Monte Carlo–simulated ECAL data.
The GNN models leverage graph representations of calorimeter clusters, treating energy deposits as nodes and spatial relationships as edges, achieving improved flexibility and interpretability.
