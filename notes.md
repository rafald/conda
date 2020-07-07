### Conda notes

#### default packages present in each new env: ipython pip
    conda config --append create_default_packages  ipython
    conda config --append create_default_packages  pip

#### how to create new jupyter environment ('conda install jupyter' OR 'pip install' inside conda env)
    conda create -n jupyter
    conda activate jupyter
    pip install jupyter

#### VScode renders jupiter notebooks, very lightweight
It requires installation of python vscode extention (by Microsoft)

