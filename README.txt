

### Create conda environment

```
# Create the environment and name it ts
conda env create -n ts python=3.8 

# Install Data Science Libraries
conda install pandas xgboost scikit-learn seaborn 

# Install statsforecast
conda install -c conda-forge statsforecast

# Not run for the first lectures
# conda install -c conda-forge statsforecast mlforecast hierarchicalforecast 
# conda install -c conda-forge neuralforecast

# Install so the environment can be accesed from jupyter notebooks
conda install -c anaconda ipykernel
```
