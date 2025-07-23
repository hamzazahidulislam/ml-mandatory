# ml-mandatory

## [Firstly, you have to install Miniconda](https://www.anaconda.com/docs/getting-started/miniconda)

## Active minconda base conda environment


` eval "$(/home/user/miniconda3/bin/conda shell.YOUR_SHELL_NAME hook)" `


## After Active base conda environment 

`conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter`

## Shift your base conda environment to your specific project conda environment 

`conda activate /home/user/Desktop/test-ml/env`


## If you miss something later, you use this command to download 
`conda install jupyter`


