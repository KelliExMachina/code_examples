# Virtual Environments

## conda environment commands

```python

conda env list

conda update -n base conda
conda config --add channels conda-forge

conda create --name scrape_twit python=3.8
conda activate scrape_twit
conda install -y scrape_twit install pandas jupyter -y
conda install -y numpy
conda install -y requests


conda remove --name scrape_twit <package> or -all
conda env export > environment.yml

conda env remove --name <environment>
conda env create -f environment.yml

pip install --upgrade pip
pip install -y json oauth3
pip download cupy

python -m pip freeze > requirements.txt
python -m pip install -r requirements.txt



which python


```


## basic

```python
# Environment setup

conda update conda

conda -c mlenv python=3.7 conda

# install environment kernels so that jupyter will work with this new environment
pip install environment_kernels

# install ml package
conda install -c conda-forge imbalanced-learn

# initialize so that conda will work with current path variables
conda init bash # or zsh if mac

# install new environment in jupyter
python -m ipykernel install --user --name mlenv
python -m ipykernel install --user --name learn-env
python -m ipykernel install --user --name PythonData
```





## face_recognition  

```python
conda update -n base conda
conda config --add channels conda-forge  
conda config --add channels menpo   
conda create --name face-recognition python=3.5  
source activate face-recognition
conda install -y piconda install -y cmake
conda install -y scikit-learn  
conda install -y scikit-image
conda install -y opencv3   
pip install face-recognition  
conda install -y numba cudatoolkit
pip install cupy
pip download cupy
git clone https://github.com/KelliExMachina/cupy.git
cd cupy
pip install .

conda env create -f environment.yml
conda env export > environment.yml
SIFT in the main repository

conda remove --name face-detection <package>
conda env remove --name <environment>
```

## mapping

```python
conda create --name basemap python=3.5
source activate basemap
(basemap)$ conda install -y scikit-learn
(basemap)$ conda install -y -c conda-forge scikit-image
pip install --upgrade pip

conda remove --name basemap --all

```

## language_voice

blah

## base

```python
conda create --name python3.5 python=3.5
source activate python3.5
conda install -y scikit-learn
conda install -y -c conda-forge scikit-image
conda install -y pip
conda install -y pandas

```

## learn.co

```python
git clone git clone https://github.com/learn-co-curriculum/dsc-data-science-env-setup-v2-1.git
cd ~/Documents/GitHub/dsc-data-science-env-setup-v2-1
conda update -n base conda
conda env create -f environment.yml
conda activate learn-env 
echo "conda activate learn-env" >> ~/.bash_profile

```
