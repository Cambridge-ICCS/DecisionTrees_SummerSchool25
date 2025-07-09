# Decision Trees and Random Forests

This repository contains Jupyter notebooks for teaching and exploring **Decision Tree** and **Random Forest** models using standard datasets.

You will learn how to:
- Use Random Forest for **regression** 
- Use Random Forest for **classification** 
- Visualise trained trees and feature importances
- Evaluate models using standard metrics

---

## Prerequisites

- Python 3.8+
- Basic understanding of supervised machine learning
- Familiarity with Jupyter Notebooks and Python syntax

---

## Running the notebooks using vscode or any other IDE

### 1. Clone the Repository

```bash
git clone https://github.com/surbhigoel77/DecisionTrees_SummerSchool25.git
cd DecisionTrees_SummerSchool25
```

### 2. Create a Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```
Note: If running requirements.txt gives error, try upgrading pip using command `pip install --upgrade pip`

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```


## Running the notebooks using Codespace
Use the below commands in your codespace terminal

### 1. Install notebook package using,
 ```bash
pip install notebook
```

### 2. Install ipykernel package and add it to your environamnt using,
 ```bash
pip install ipykernel
```
 ```bash
python -m ipykernel install --user --name=codespace-env --display-name "ICCS Codespace"
```

### 3. Launch notebooks (in your browser) using,
```bash 
jupyter notebook --ip=0.0.0.0 --port=8888 --no-browser --allow-root --NotebookApp.token='' --NotebookApp.password='' 