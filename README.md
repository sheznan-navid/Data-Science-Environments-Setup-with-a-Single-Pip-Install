# Data-Science-Environments-Setup-with-a-Single-Pip-Install

# Step 1: go to desktop 
cd desktop

# step 2: create a project directory folder
mkdir data_analytics

# step 3: enter the project folder
cd data_analytics

# step 4: setup environment
conda create --name datascienv python=3.9 -y

# step 5: activate enviroment
conda activate datascienv

# step 6: install all related packages
pip install -U datascienv
