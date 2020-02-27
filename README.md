# conda

## the packages to install by default for each new env 
conda config --append create_default_packages  ipython
conda config --append create_default_packages  pip

## vscode requires jupyter package installed by pip ('conda install jupyter' does not work)
conda uninstall jupyter
conda create -n jupyter
conda activate jupyter
pip install jupyter

