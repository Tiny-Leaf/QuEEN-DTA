<p align="left"><a href="https://github.com/CoffeeIsAllYouNeed/QuEEN-DTA/actions/workflows/python-app.yml"><img src="https://img.shields.io/github/actions/workflow/status/CoffeeIsAllYouNeed/QuEEN-DTA/python-app.yml?branch=main&label=Unit%20tests" alt="Unit tests"></a> <img src="https://img.shields.io/badge/python-3.12.12-blue.svg" alt="Python version"> <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License"> <a href="https://doi.org/10.5281/zenodo.XXXXXX"><img src="https://img.shields.io/badge/DOI-10.5281%2Fzenodo.XXXXXX-blue.svg" alt="DOI"></a></p>

## QuEEN-DTA

QuEEN-DTA stands for "Quantum-Extreme-Embedding-Network for Drug-Target Affinity". It uses a novel neural network architecture consisting of multi-head embeddings for input sequence, quantum  embeddings for physicochemical features to produce accurate results as compared to state-of-the-art (SoA) models.


## Installation 

### Prerequisites
[1] Ensure the system has Python **3.12.12** .

[2] Code is written in accordance to assumption that multi-GPU setup is being used, as for our case we used NVIDIA T4 x 2. 

### 1. Clone the Repository

```bash
git clone [https://github.com/CoffeeIsAllYouNeed/QuEEN-DTA.git](https://github.com/CoffeeIsAllYouNeed/QuEEN-DTA.git)
cd QuEEN-DTA

```

### 2. Create a Virtual Environment

```bash
python -m venv queen_env

# On macOS/Linux:
source queen_env/bin/activate
# On Windows (Command Prompt):
queen_env\Scripts\activate.bat
# On Windows (PowerShell):
queen_env\Scripts\Activate.ps1

```

### 3. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt

```

### 4. Run main.py file 
```bash
python main.py

```