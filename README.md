# Starbucks promotion exercise

### Summary
This project is a recommendation exercise provided by Starbucks.
The goal is to investigate customers receptiveness towards promotion for a product.
The setup is very simplified. There is no time dependency and only one product considered.
It covers training and test data of customers with their specifics and the information whether a promotion was sent and the product bought afterwards.

### Motivation
This project covers a simple real life problem of shops, restaurants, or cafés in how to advertise he right customers that are willing to pay for offered products.
From their specifics one can learn improve intuition in the marketing campaigns.

### Data sources: 

### Install/run instructions:
1. Install python >= 3.11 and the packages denoted in requirements_working_configuration.txt preferably in a virtual environment as exemplarily shown for the windows command prompt:
```
      projectfolder:> python -m venv .venv
      projectfolder:> cd .venv\Scripts
      projectfolder\.venv\Scripts> .\activate.bat
      projectfolder\.venv\Scripts> cd ..\..
      projectfolder:> python -m pip install -r requirements_working_configuration.txt
```
      Within your project folder "projectfolder" use the "python" command as long as the virtual environment is activated
      (if not working with/on the project, the virtual environment should be deactivated by executing projectfolder\.venv\Scripts\deactivate.bat).

      Important note: If you are using requirements.txt (no package versions provided) instead of requirements_working_configuration.txt, make shure to install ipykernel before (python -m pip install ipykernel). The order seems important.

2. In the programming IDE select .venv\Scripts\python.exe as Kernel.

1. Run all code blocks in "Starbucks.ipynb"

### Files in the repository
```
Starbucks.ipynb                        # main jupyter file
README.md
requirements.txt                       # list of required packages
requirements_working_configuration.txt # list of packages covering a working configuration
Test.csv                               # test data
test_results.py                        # python file for testing the promotion strategy - it is referred in the main jupyter file
training.csv                           # training data
```