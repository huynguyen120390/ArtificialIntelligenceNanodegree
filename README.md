# Artificial_Intelligence_Nanodegree
Projects completed in Artificial Intelligence Nanodegree

## A.Set up:
## 1. Set up Anaconda 64bit or 33 bit for Windows, Mac, Linux: 
  #### https://www.anaconda.com/download/
  If you are seeing the following "conda command not found" and are using ZShell, you have to do the following:Add
  #### export PATH="/Users/username/anaconda/bin:$PATH" to your .zsh_config file.
  Extra Reading:
  #### https://jakevdp.github.io/blog/2016/08/25/conda-myths-and-misconceptions/
          
## 2. Common Conda Commands in Terminal:
#### >> conda list : to view lists of packages in current environment
#### >> conda install package_names : install packages
#### >> conda remove package_names : remove packages
#### >> conda update package_names : update packages
#### >> conda upgrade conda
#### >> conda upgrade --all
#### >> conda search *imcomplete_package_name* : search incomplete package name
#### >> conda create -n environment_name package_names : create a new environment with initial packages
#### >> conda create -n environment_name python=3.6 package_names : create a new environment with python 3.6 and other packages
#### >> OS/Linux: source activate environment_name
#### >> Windows: activate environment_name
#### >> OS/Linux : source deactivate environment_name
#### >> Windows: deactivate environment_name
#### >> conda env list : list all environments 
#### >> conda env remove -n environment_name

## 3. Share environments:
#### >> conda env export > environment_name.yaml
#### >> conda env create -f environment_name.yaml

### Using '>>pip freeze' to create appropriate requirement file with pip:
#### $ env1/bin/pip freeze > requirements.txt
#### $ env2/bin/pip install -r requirements.txt


