# Jupyter Notebooks

> **Status: archived.** A small collection from 2021, kept as a reference. It is not being extended.

Notebooks from when I was learning math and symbolic computation with Python. GitHub renders
`.ipynb` files directly, so you can read them here without installing anything.

## Index

| Notebook | About | Libraries |
|---|---|---|
| [sympy_example.ipynb](./sympy_example.ipynb) | The first steps with [SymPy](https://www.sympy.org): create a symbol (`Symbol("x")`) and build an expression from it. `3*x + 20*2` shows up as `3*x + 40`: Python evaluates `20*2` first and SymPy keeps the symbolic part | `sympy` |

## Run them yourself

In the browser, with nothing to install:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/UltiRequiem/jupyter_notebooks/HEAD?labpath=sympy_example.ipynb)

Or locally:

```sh
git clone https://github.com/UltiRequiem/jupyter_notebooks
cd jupyter_notebooks
python3 -m venv .venv && . .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Where to go next

- [SymPy tutorial](https://docs.sympy.org/latest/tutorials/intro-tutorial/index.html), the official step-by-step guide
- [Jupyter documentation](https://docs.jupyter.org)

## License

All here is licensed under the [MIT License](./LICENSE.md).
