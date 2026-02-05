# GrooveGen: Input-Conditioned Drum Loop Generator

## Contributors
- Ethan Kusnadi
- Avinash Duggal

## Overview
GrooveGen is a generative model that creates realistic, stylistically controlled **4-bar drum grooves** from a user prompt such as **"funk 100 BPM"**. It trains a **Conditional Variational Autoencoder (CVAE)** on the **Google Groove MIDI Dataset (GMD)** and generates new sequences conditioned on a **19-dimensional tag vector** (**18 genres + normalized BPM**).

## Project Structure
- **Report:** `GrooveGen_ Input-Conditioned Drum Loop Generator.pdf`  
  Full write-up describing the motivation, data pipeline, CVAE architecture, and evaluation.
- **Notebook:** `groove_gen.ipynb`  
  End-to-end implementation of GrooveGen, including dataset loading and preprocessing, HOV conversion, CVAE model definition, training, and evaluation/visualization.

## Dataset License
This project uses the **Google Groove MIDI Dataset (GMD)**. The dataset is made available by Google LLC under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.
- Dataset page: https://magenta.withgoogle.com/datasets/groove
- License text: https://creativecommons.org/licenses/by/4.0/
