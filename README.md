# Movie Reccomendation Project

## Setup Instructions

### 1. Clone the repository

```bash
git clone <your-repo-link>
cd <your-project-folder>
```

### 2. Create a virtual environment (Optional)

```bash
python -m venv venv
```

### 3. Activate the environment (Optional)

**Mac/Linux:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 5. Data
The dataset CSV is too large to be included in this repository.

The data is in the data folder. Make sure this folder is in the main project folder.

Then run 01_data_prep which will create the training and testing CSV from the data in the data folder. The test CSV may also be included separately if space allows.

After data is prepped, it should automatically be in the project folder for use:

project/train.csv
project/test.csv
project/users_movies.csv

## Run the Project

### Jupyter Notebook/Lab

```bash
jupyter notebook
```

Then open the main notebook file.


## Requirements

All dependencies are listed in `requirements.txt`.

---

## Reproducibility

* Python 3
* Random seed = 42

---
