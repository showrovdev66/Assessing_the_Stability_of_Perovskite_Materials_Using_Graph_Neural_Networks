# Assessing_the_Stability_of_Perovskite_Materials_Using_Graph_Neural_Networks

## Overview

### Project Purpose
The primary objective of this project is to assess the stability of perovskite materials using Graph Neural Networks (GNNs). By analyzing the structural and compositional features of these materials, we can predict their stability, which is crucial for various applications in materials science.

### Key Outputs
**A. Model Training and Evaluation Results:**

After training the model for 100 epochs, the following accuracies were achieved:
- **Training Accuracy**: 89.37%
- **Test Accuracy**: 86.01%

These results indicate that the model is effective in classifying perovskite materials as stable or unstable based on their features.

## Dataset
The dataset used in this project contains various properties of potential perovskite materials, including:
- **Material Composition**: Chemical formulas for perovskite materials.
- **A-site, B-site, and X-site Elements**: Elements occupying different sites in the perovskite structure.
- **Energetic Properties**: Values such as formation energy and energy above the convex hull, which are key indicators of material stability.
- **Physical and Chemical Properties**: Various attributes related to the constituent elements.

### Key Features:
- **energy_above_hull (meV/atom)**: A measure of stability, with lower values indicating greater stability.
- **formation_energy (eV/atom)**: The energy required to form the material, also related to stability.
- **Elemental Properties**: Features like heat of vaporization, ionization energy, density, and more.

## Project Structure
- **data/**: Contains the dataset used for training and testing.
- **notebooks/**: Jupyter notebooks for exploratory data analysis and model training.
- **src/**: Source code for graph creation, GNN implementation, and training scripts.
- **requirements.txt**: List of required Python packages for the project.


