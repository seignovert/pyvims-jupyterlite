PyVIMS on JupyterLite
=====================
- License: [BDS 3-Clause](LICENSE.md)

> [!warning]
> At the moment, `PyVIMS` does not support data download in jupyterlite context. You need to attach the cube with the notebook or upload them at runtime.

Gitlab Pages
------------
Try it online: [vims.univ-nantes.io/python/jupyterlite/](https://vims.univ-nantes.io/python/jupyterlite/lab/?path=PyVIMS.ipynb)

Notebook.link
-------------
A clone of this repo is available on [github.com](https://github.com/seignovert/pyvims-jupyterlite/) to use it directly with [notebook.link](https://notebook.link/).

You can also try it online: https://notebook.link/@seignovert/pyvims

Local build
-----------

> [!warning]
> To build this project you will need [micromamba](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html)
> and [uv](https://docs.astral.sh/uv/) to be installed locally.

To build the notebooks with JupyterLite Xeus:
```bash
uv run jupyter lite build
```
