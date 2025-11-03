# CSB410_Project1

## Repository Setup
To set up the project environment, follow these steps:

Clone the Repository: Open your terminal or command prompt and run the following command to clone the project repository:
    cd <repository_name>
    conda env create -f requirements.yml
    conda activate <environment_name>

name: <environment_name>  # Replace with a suitable name for your environment
channels:
  - conda-forge
  - defaults
dependencies:
  - python=3.9  # Specify the Python version used in the notebook
  - numpy
  - matplotlib
  - seaborn
  - tensorflow
  - scikit-learn
