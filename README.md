# Alan
AI Audio Chatbot



Installation and Setup
Follow these steps to set up the project environment:

## 1. Python Virtual Environment Setup
Prerequisites
Python installed
Create and Activate Virtual Environment
Open a terminal or command prompt and navigate to the project directory:

#### bash
cd your_project_directory
Create a Python virtual environment:

#### bash
# Using venv (built-in to Python)
python -m venv venv_name
# Activate the virtual environment
# On Windows
venv_name\Scripts\activate
# On macOS/Linux
source venv_name/bin/activate
## 2. Install Dependencies
Once the virtual environment is activated, install project dependencies using pip and the provided requirements.txt file:

#### bash
pip install -r requirements.txt
This will install all necessary packages into your virtual environment.

## 3. Jupyter Notebook Kernel Configuration
Anaconda Kernel
Ensure that the Jupyter Notebook uses the correct kernel tied to your virtual environment:

Install Jupyter Notebook if not already installed:

bash
pip install jupyter
Add the virtual environment as a kernel to Jupyter:

bash
python -m ipykernel install --user --name=venv_name --display-name="VirtualEnvName"
Replace venv_name with the name of your virtual environment and "VirtualEnvName" with the name you want to display in Jupyter.

Open Jupyter Notebook:

bash
jupyter notebook
In the notebook interface, select the correct kernel ("VirtualEnvName") from the Kernel menu > Change Kernel.
