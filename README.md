# GOSTNetsBook
Sample page for GOSTnets Jupyterbook Development

## Packages
* [jupyter-book](https://jupyterbook.org/en/stable/start/overview.html)
* [ghp-import](https://jupyterbook.org/en/stable/start/publish.html)

## Commands
### Jupyter-book
To install jupyter-book, run the following command using anaconda prompt
```
pip install -U jupyter-book
```
To create the inital template, run:
```
jupyter-book create GOSTNetsBook/
```

### ghp-import
To install ghp-import, run:
```
pip install ghp-import
```

To push the html files from a build folder update to the autogenerated gh-pages branch, run:
```
ghp-import -n -p -f _build/html
```
