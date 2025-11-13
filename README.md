# UC-25-Summer-DATA601-AI-Agents

Hi there 👋  
Welcome to the **UC-25-Summer-DATA601-AI-Agents** project!

This guide explains how every team member should correctly set up the development environment.

---


## 📁 Project Structure Overview

Below is the directory structure of the **AI-Agents** project, along with explanations for what each folder is used for.

AI-Agents/

data/ ← Raw data, cleaned data, datasets used in experiments

src/ ← Core Python source code for the project

notebooks/ ← Jupyter/Colab notebooks for experiments, explorations, demos

models/ ← Saved models, checkpoints, exported weights

config/ ← Configuration files (prompts, model settings, parameters, paths)

tests/ ← Unit tests and validation scripts

.gitignore ← Git ignore rules

README.md ← Project documentation and setup guide

LICENSE ← Project license

environment.yml ← Conda environment configuration

## 🌱 Environment Setup (Required for All Team Members)

### 1. Install Miniconda

Download Miniconda from the official website (choose **Windows 64-bit** if on Windows).

During installation, make sure to select:

- ✔ **Just Me** (recommended)  
- ✔ **Add Miniconda3 to my PATH environment variable**  
- ✔ **Register Miniconda3 as my default Python 3**

After installation, restart your computer once to ensure PATH variables are applied.


### 2. Clone the Project

Open a terminal and run:

git clone https://github.com/UC-25-Summer-DATA601-AI-Agents/UC-25-Summer-DATA601-AI-Agents

cd UC-25-Summer-DATA601-AI-Agents


###  3. Create and Activate the Conda Environment
Run:
conda env create -f environment.yml
conda activate UC-25-Summer-DATA601-AI-Agents

Verify the Python version:
input: python -V

Expected output:
Python 3.10.x

(Our environment is locked to Python 3.10 for compatibility.)


### 4. VS Code Setup (Very Important)
✔ Set the Default Terminal to Command Prompt (cmd.exe)

In VS Code, press:
Ctrl + Shift + P

Search for:
Terminal: Select Default Profile

Select:
Command Prompt

✔ Open a New Terminal and Activate the Environment
conda activate UC-25-Summer-DATA601-AI-Agents

✔ Select the Project Python Interpreter
Press: Ctrl + Shift + P
Choose: Python: Select Interpreter
Select: UC-25-Summer-DATA601-AI-Agents (conda)

## 🎉 You’re All Set!

You can now run Python scripts, Jupyter notebooks, APIs, and all components of this project within the configured environment.

## 📝 Notes for Team Members

Do NOT change the Python version. It must remain Python 3.10.

Always activate the environment before running code: conda activate UC-25-Summer-DATA601-AI-Agents

If you encounter terminal issues in VS Code, switch back to cmd.exe, not PowerShell.

