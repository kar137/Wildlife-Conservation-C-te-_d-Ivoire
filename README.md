# Wildlife Conservation Côte d'Ivoire

![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)

## Overview

This repository contains code and Jupyter Notebooks for deep learning and computer vision applications in wildlife conservation, specifically for identifying animal species in camera trap images from Côte d'Ivoire. The project is developed as part of the **AI Lab: Deep Learning for Computer Vision** course by [WorldQuant University](https://www.wqu.edu/).

## Features

- **Data Exploration:** Analyze and visualize datasets of camera trap images.
- **Image Processing:** Load, transform, and display wildlife images.
- **PyTorch Tensor Operations:** Hands-on tutorials for tensor creation, slicing, aggregation, and device (CPU/GPU) management.
- **Class Distribution Analysis:** Visualize class frequencies in the dataset.
- **(Optional/Extendable) Model Development:** Build and evaluate deep learning models for multi-class image classification.

## Directory Structure
```
├── 011-image-as-data (2).ipynb # Main notebook for tensor manipulation and data exploration
├── data_p1/ # Dataset root directory
│ └── data_multiclass/ # Contains training images for multiple classes
│ └── train/ # Training data directory
│ ├── antelope_duiker/
│ ├── bird/
│ ├── blank/
│ ├── civet_genet/
│ ├── hog/
│ ├── leopard/
│ ├── monkey_prosimian/
│ └── rodent/
├── README.md 
```

## Getting Started

### Prerequisites

- Python 3.11 or newer
- [Jupyter Notebook](https://jupyter.org/)
- [PyTorch](https://pytorch.org/)
- [TorchVision](https://pytorch.org/vision/stable/index.html)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pillow (PIL)](https://pillow.readthedocs.io/en/stable/)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/kar137/Wildlife-Conservation-C-te-_d-Ivoire.git
    cd Wildlife-Conservation-C-te-_d-Ivoire
    ```

2. **(Optional) Create a virtual environment and install dependencies:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```

3. **Start Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

4. **Open** `011-image-as-data (2).ipynb` **and follow the instructions in the notebook.**

### Data

- **Path:** `data_p1/data_multiclass/train/`
- **Classes:** `hog`, `blank`, `monkey_prosimian`, `antelope_duiker`, `leopard`, `civet_genet`, `bird`, `rodent`
- **Format:** Each class is a folder containing JPEG images.

> **Note:** Due to size and licensing, raw image data is not included in this repository. Please organize your own data in the same folder structure, or contact the maintainer for details.

## Usage Guidelines

This repository and its contents are licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/).

You **can**:
- ✓ Download and use this code for personal, educational, or research purposes.
- ✓ Share this repository or files publicly with attribution.

You **must**:
- ✓ Credit [WorldQuant University](https://www.wqu.edu/) for the creation of this material.
- ✓ Provide a [link to the license](https://creativecommons.org/licenses/by-nc-nd/4.0/).

You **cannot**:
- ✗ Create derivatives or adaptations of this content.
- ✗ Use this material for commercial purposes.

## Acknowledgements

- Developed as part of the [WorldQuant University](https://www.wqu.edu/) AI Lab curriculum.
- Data and project concept inspired by biodiversity and conservation efforts in Côte d'Ivoire.

## License

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---
