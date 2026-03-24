PyVIMS on JupyterLite
=====================
_2026-03-24 - B. Seignovert_

- Try it: https://vims.univ-nantes.io/python/jupyterlite/

- Source: https://gitlab.univ-nantes.fr/vims/python/jupyterlite
- License: [BDS 3-Clause](LICENSE.md)

Local install
-------------
This project use [micromamba](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html) to manage its dependencies.
You need to install it first, then copy this repo and do:
```bash
micromamba create -f environment.yml
```

To run the notebooks locally with JupyterLab:
```bash
micromamba run -n pyvims-jupyterlite jupyter lab notebooks/
```

To export all the notebook with JupyterLite:
```bash
micromamba run -n pyvims-jupyterlite jupyter lite build
```
