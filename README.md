# ENCN423 Tutorial Notebooks
Jupyter notebooks for weekly ENCN423 tutorials

## Cloud access: 

Use the buttons below to access the notebook in your browser (no installations required!)
Week 1: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/beccapeer/encn423/HEAD?labpath=Wiki_ono.ipynb)

## Local Installation:

Ensure you have Anaconda Python (minimum version 3.6) installed. Then

1. Clone the repo

```bash
git clone https://github.com/beccapeer/encn423
```

2. CD into the repo and create a conda environment

```bash
cd encn423
conda env create -f environment.yml
conda activate encn423_env
```

3. Add the conda environment so it is accessible from the Jupyter Notebook

```bash
python -m ipykernel install --user --name=encn423_env
```

## Use

If you are a local user, open a Jupyter Notebook server from the terminal

```bash
jupyter notebook
```

In the local server, or via the binder link, open the notebook for this week (e.g., `Wiki_ono.ipynb`). In the local server, select the `encn423_env` environment in `Kernel > Change kernel`.

Write code and run the notebook cells.

Tutorial questions are on Learn for each week.

## Author

Rebecca Peer (Civil and Natural Resource Engineering, University of Canterbury)
