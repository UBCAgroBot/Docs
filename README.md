# Docs for Agrobot

## Setting up the environment

- Install [python 3.9](https://www.python.org/downloads/release/python-3910)
- Install [anaconda](https://docs.anaconda.com/anaconda/install/index.html)
- Open [Anaconda Prompt](https://docs.anaconda.com/anaconda/user-guide/getting-started/#open-anaconda-prompt)
  - run `conda config --add channels conda-forge`
  - run `conda install jupyterlab jupyterlab-spellchecker nb_conda_kernels`
  - create a new virutal environment (kernel): `conda env create -f agrobotenv.yml` (make sure that [agrobotenv.yml](agrobotenv.yml) is in the working directory)
  - Activate the environment with `conda activate agrobot`

Click [here](https://ubc-cs.github.io/cpsc330/docs/setup.html) for a more detailed setup guide.
