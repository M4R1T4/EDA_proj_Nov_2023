# Data Science EDA Project November 2023

# The Task

- Given is the King County Housing Data: This dataset contains information about home sales in King County (USA)
- the aim is to find at least 3 recommendations for the clients through EDA/statistical analysis
- ***The Client:*** 
   + William Rodriguez
   + Buyer
   + 2 people
   + wants two houses 
   + country (best timing & non-renovated)
   + city house (fast & central location)
     
# The Deliverables

- the repository contains a Power Point presentation as pdf in which I have summarised and presented the findings from the EDA 
- There are also 2 Jupyter notebooks:
  + the 1st notebook contains the data cleaning
  + the 2nd notebook contains the EDA including the plots I created for the presentation 


# Setup


## Requirements

- pyenv
- python==3.11.3


## Set up the Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.


### **`macOS`** type the following commands : 


- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
 

 **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```
