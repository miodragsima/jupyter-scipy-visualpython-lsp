# jupyter-scipy-visualpython-lsp
Scientific JupyterHub notebook image for Kubernetes and Olares OS. Based on beclab/jupyter-scipy-notebook with NumPy, Pandas, SciPy, Matplotlib and Scikit‑learn. Extended with Visual Python JupyterLab widget and Python LSP server for IDE‑like development.

JupyterHub Scientific Computing Image with Visual Python & LSP for Olares OS
----------------------------------------------------------------------------

This Docker image is built for JupyterHub deployments on Kubernetes and optimized for Olares OS.
It is based on the official scientific computing stack
docker.io/beclab/jupyter-scipy-notebook:notebook-7.0.6
and extends it with advanced developer productivity features.
Scientific Computing Stack
The image includes a full-featured scientific Python environment with:

NumPy for numerical computing
Pandas for data manipulation and analysis
SciPy for scientific and technical computing
Matplotlib for visualization
Scikit-learn for machine learning

This makes it well-suited for data science, research, and scientific workflows.
Added Productivity Features

✅ Visual Python JupyterLab widget for visual, interactive code assistance
✅ JupyterLab Language Server Protocol (jupyterlab-lsp)
✅ Python Language Server (python-lsp-server) enabling:

intelligent autocompletion
inline diagnostics
code navigation and introspection


✅ Fully compatible with JupyterLab 4.x

Benefits for JupyterHub on Kubernetes

IDE-like Python development experience directly in JupyterLab
All UI extensions are preinstalled in the image (no runtime installs)
Stable and reproducible behavior across user server restarts
Designed for multi-user JupyterHub environments under Olares OS

Intended Use

Scientific computing and data analysis notebooks
Python development with enhanced editor capabilities
JupyterHub deployments requiring persistent UI extensions on Kubernetes
