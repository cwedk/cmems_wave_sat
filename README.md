Openda enviroment to explore 1d, 2d simplified versions of the openda-swan tests for the EnkF. Openda configs are stored under models/.../config/

```sh
git clone git@github.com:cwedk/cmems_wave_sat.git 
```

Make sure you have conda/mamba. Install the environment cmems_sat_lab from the environment.yml

Install openda-lab environment.


```sh
conda env create -f environment.yml
```

Launch jupyter lab


```sh
conda activate cmems_sat_lab
```

```sh
cd notebooks
jupyter lab
```
or with vscode

```sh
code 01-explore-results.ipynb
```

choose cmems_sat_lab  environment in kernel