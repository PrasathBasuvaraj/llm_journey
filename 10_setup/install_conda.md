# 🚀 Conda Installation Guide

**Welcome to the Conda setup guide!** 🎯 This guide will help you install and configure **Conda**, a lightweight environment manager for running Jupyter notebooks efficiently.

---

## **🛠️ Prerequisites**

Before installing Conda, ensure you have the following:  
✔️ **Python 3.8+** installed ([Download here](https://www.python.org/downloads/))  
✔️ **Git** installed ([Download here](https://git-scm.com/downloads))  
✔️ **pip** (Python package manager)

---

## **🚀 Step 1: Install Conda**

Run the following command to install Conda:

```sh
pip install conda
```

Once installed, verify it with:

```sh
conda --version
```

---

## **📂 Step 2: Create a Conda Environment**

Now, create an isolated Conda environment for your Jupyter notebooks:

```sh
conda env create -f environment.yml
```

This sets up a new environment named **llm-journey**.

Activate it with:

```sh
conda activate hyppar-llms
```

Check if everything is installed correctly:

```sh
conda list
```

Or see the environment info:

```sh
conda info --envs
```

---

## **📦 Step 3: Install Essential Packages**

Inside the Conda environment, install the necessary Python libraries:

```sh
pip install jupyterlab numpy pandas matplotlib seaborn scikit-learn
```

These libraries will help with data analysis, visualization, and AI experiments.

---

## **💻 Step 4: Verify Installation**

Launch Jupyter to confirm that everything is working:

```sh
jupyter lab
```

This will open **JupyterLab** in your browser.

---

## **🔄 Step 5: Managing the Conda Environment**

- **Deactivate the environment** when not in use:

  ```sh
  conda deactivate
  ```

- **List all Conda environments**:

  ```sh
  conda env list
  ```

- **Delete an environment** (if needed):

  ```sh
  conda env remove --name hyppar-llms
  ```

---

## **📌 Additional Configuration**

To ensure smooth execution, you may want to set up automatic activation for your environment. Add the following line to your terminal profile (`~/.bashrc`, `~/.zshrc`, or equivalent):

```sh
export PATH="$HOME/.conda/bin:$PATH"
```

Then reload your shell:

```sh
source ~/.bashrc  # or source ~/.zshrc
```

If you want Jupyter to recognize Conda environments, install `nb_conda_kernels`:

```sh
pip install nb_conda_kernels
```

This will allow you to select conda environments directly from Jupyter Notebook.

---
