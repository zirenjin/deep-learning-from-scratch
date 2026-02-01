# Deep Learning from Scratch - Environment Setup

This project is based on Python3 and Jupyter Notebook. It is the author's personal learning note of the book *Deep Learning from Scratch* by Koki Saitoh
Below is the instruction to set up your environment in a **Unix-based System**

## 1. Initialize Virtual Environment

To prevent dependency conflicts, it is recommended to create a separate virtual environment. Please open your terminal in the project's root directory and follow these steps:

### Step 1: Create a environment
```bash
python3 -m venv venv
```

### Step 2: Activate the environment
```bash
source venv/bin/activate
```

### Step 3: Install Dependencies

#### 1. Upgrade pip
```bash
pip install --upgrade pip
```
#### 2. Install dependencies
##### numpy: Scientific Computing
##### matplotlib: Creating static, animated, and interactive visualizations
##### ipykernel: for running Jupyter Notebook on VS Code
```bash
pip install numpy 
pip install matplotlib 
pip install ipykernel
```