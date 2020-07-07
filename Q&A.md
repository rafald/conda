## conda

### default packages present in each new env
    conda config --append create_default_packages  ipython
    conda config --append create_default_packages  pip

### how to create new jupyter environment (conda install or pip install inside conda env)
    conda create -n jupyter
    conda activate jupyter
    pip install jupyter

### vscode renders jupiter notebooks. It requires installation of python vscode extention (by Microsoft)

