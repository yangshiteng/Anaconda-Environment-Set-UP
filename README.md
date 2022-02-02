# Anaconda Code

## 1. check conda version

conda --version

## 2. update conda

conda update conda

## 3. create new conda environment

conda create --name [environment name] python=[python version such as 3.9] [packages]

if failed, try this code before the creation: conda config --set ssl_verify false

## 4. activate new environement

conda activate [environment name]

## 5. To see a list of all your environments

conda info --envs

## 6. Change your current environment back to the default (base)

conda activate

## 7. Verify which version of Python is in your current environment:

python --version

## 8. Check to see if a package you have not installed is available from the Anaconda repository (must be connected to the Internet):

conda search [package name]

## 9. Install package into the current environment:

conda install [package name]

## 10. Check installed packages

conda list

# VS code 

## 1. virtual environment 

python -m venv [environment name] python=[version]

