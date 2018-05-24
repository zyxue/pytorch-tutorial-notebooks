This repo simply host a Jupyter notebook version of the PyTorch tutorials at
https://pytorch.org/tutorials/

Contributions are welcome.

Basic format:

The top of each tutorial shows the link, and the content structure (e.g.
headers: `h2` => `##`, `h3` => `###`)follows that of the tutorial page, so does
the directory.


# Development

Create virtual environment:

```
conda env create --name pytorch -f env-conda.yml
```

Start the server

```
jupyter notebook --no-browser --ip 0.0.0.0
```

Export virtual environment:

```
conda env export --name venv-pytorch > env-conda.yml
```
