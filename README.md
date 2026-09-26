## About this repository
This repository hosts my website, which includes a section about me, my blog posts, and my analyses in both R and Python. 

## Required Installations
Quarto version 1.10.18

uv version 0.12.7

R version 4.6.1

## Instructions
Input the following steps within your terminal
### 1. Clone repository
```{bash}
git clone https://github.com/barrysiu-connect/barrysiu-connect.github.io.git
```

### 2. Change directory to folder
```{bash}
cd barrysiu-connect.github.io 
```

### 3. Sync Python virtual environmenmt
```{bash}
uv sync
```

### 4.1. Load R 
```{bash}
R
```

### 4.2. Load R virtual environment (in R)
```{bash}
renv::restore()
```

### 4.3. Exit R
```{bash}
q()
```

### 5. Render Quarto website
```{bash}
uv run quarto render
```

### 6. Launch and preview Quarto website locally
```{bash}
uv run quarto preview
```

## Dataset
For my website I used the "palmerpenguins" dataset for my data analysis which comes from base R.

## Citation
Horst AM, Hill AP, Gorman KB (2020). palmerpenguins: Palmer Archipelago (Antarctica) penguin data. R package version 0.1.0. https://allisonhorst.github.io/palmerpenguins/. doi: 10.5281/zenodo.3960218.
