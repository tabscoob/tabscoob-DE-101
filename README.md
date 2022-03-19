# Tabscoob AI data engineering 101 study group

## Resources for first part

movies dataset in kaggle:
https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

Jupyter with conda:
https://towardsdatascience.com/how-to-set-up-anaconda-and-jupyter-notebook-the-right-way-de3b7623ea4a

Jupyter configuration on vscode:
https://code.visualstudio.com/docs/datascience/jupyter-notebooks

deepnote tabscoobs:
https://deepnote.com/@Tabscoob-AI


### Create your project conda env
https://code.visualstudio.com/docs/python/environments


```{python}
conda create -n tabscoob_DE_101 python=3.9 ipykernel=6.9 jupyterlab=1.2 pandas=1.4
```

Activate environment:
```{python}
conda activate tabscoob_DE_101
```

Delete environment
```{python}
conda env remove -n tabscoob_DE_101
```


Crear branch para trabajo
```{python}
git checkout -b de_{tu nombre} main
```