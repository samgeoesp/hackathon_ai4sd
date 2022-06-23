# Setting up the environment

Best practice is to have a consistent conda environment between us to ensure everything runs smoothly. 
There is a **requirements.txt** file in this repo that should be usable to generate the conda environment. If this 
does not work then below are all packages installed into an environment called *hackathon*.

>
> conda create -c conda-forge -n hackathon rdkit
>
> conda install scikit-learn
>
> conda install -c conda-forge matplotlib 
>

This should give the following packages:

- Pandas
- Numpy
- Matplotlib
- RDKit
- Sklearn

Should we need more packages then feel free to update this document with the corresponding instructions for 
installation. 
