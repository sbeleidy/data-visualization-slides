# Data Visualization Slides

These slides are an intro and overview of Data Visualization. You can view the contents in the Jupyter notebooks or run the slides.

## Load necessary libraries

You can use pip or conda to load the necessary libraries.

### pip

```bash
pip install -r requirements.txt
```

### conda

You can use conda to set up an environment for the slides by running:

```bash
conda env create -f environment.yml
source activate data-viz-slides
```

You can learn more about conda environments on their [managing environments page](https://conda.io/docs/using/envs.html#managing-environments).

## Run locally

To run the slides use the following command:

```bash
jupyter nbconvert --to slides Data\ Visualization.ipynb --post serve
```