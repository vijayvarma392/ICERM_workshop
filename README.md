# ICERM_workshop

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vijayvarma392/ICERM_workshop/HEAD)

Notebooks for the ICERM workshop tutorials on surrogate models.

## Instructions

You have three options:

### 1. Binder

You can use
[Binder](https://mybinder.org/v2/gh/vijayvarma392/ICERM_workshop/HEAD) to run
the notebooks directly from your browser. This should work without having to
install anything.

### 2. Install dependencies yourself

You will need to install some depenencies to run the notebooks. These are listed [here](https://github.com/vijayvarma392/ICERM_workshop/blob/main/environment.yml). All of these are available through either conda or pip.

Once these are installed, you can open the notebooks using:
```shell
git clone git@github.com:vijayvarma392/ICERM_workshop.git
cd ICERM_workshop
jupyter notebook .
```

### 3. Conda

If you have conda, you can get the environment by doing:
```shell
git clone git@github.com:vijayvarma392/ICERM_workshop.git
cd ICERM_workshop
conda env create -f environment.yml
```

This will create an environment called `sur_env`. Which you can activate by
doing:
```shell
conda activate sur_env
```

If this is the first time you are using environments, you may first need to do
somthing like:
```shell
conda init bash
```

Once the environment is activated, you should be able to open the notebooks from
within the `ICERM_workshop` repo using:
```shell
jupyter notebook .
```

To exit from this environment, do:
```shell
conda deactivate
```


