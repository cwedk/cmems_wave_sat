Notebook code examples to download and explore wave satellite altimetry from CMEMS

```sh
git clone git@github.com:cwedk/cmems_wave_sat.git 
```

Make sure you have conda/mamba. Install the environment cmems_sat_lab from the environment.yml


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
code 01-get_sat_data.ipynb
```

choose cmems_sat_lab  environment in kernel