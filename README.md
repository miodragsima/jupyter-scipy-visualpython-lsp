# jupyter-scipy-visualpython-lsp

Scientific JupyterHub notebook image for Kubernetes and Olares OS. Based on beclab/jupyter-scipy-notebook with NumPy, Pandas, SciPy, Matplotlib and Scikit‑learn. Extended with Visual Python JupyterLab widget and Python LSP server for IDE‑like development.

JupyterHub Scientific Computing Image with Visual Python & LSP for Olares OS
This Docker image is built for JupyterHub deployments on Kubernetes and optimized for Olares OS. It is based on the official scientific computing stack docker.io/beclab/jupyter-scipy-notebook:notebook-7.0.6 and extends it with advanced developer productivity features.

# Scientific Computing Stack

The image includes a full-featured scientific Python environment with:
*NumPy for numerical computing
*Pandas for data manipulation and analysis
*SciPy for scientific and technical computing
*Matplotlib for visualization
*Scikit-learn for machine learning
This makes it well-suited for data science, research, and scientific workflows. 

# Added Productivity Features  
  ✅ Visual Python JupyterLab widget for visual, interactive code assistance  
  ✅ JupyterLab Language Server Protocol (jupyterlab-lsp)  
  ✅ Python Language Server (python-lsp-server) enabling:

intelligent autocompletion inline diagnostics code navigation and introspection

  ✅ Fully compatible with JupyterLab 4.x

# Benefits for JupyterHub on Kubernetes

IDE-like Python development experience directly in JupyterLab
All UI extensions are preinstalled in the image (no runtime installs)
Stable and reproducible behavior across user server restarts
Designed for multi-user JupyterHub environments under Olares OS
Intended Use

Scientific computing and data analysis notebooks
Python development with enhanced editor capabilities
JupyterHub deployments requiring persistent UI extensions on Kubernetes

# License

## Based on beclab/jupyter-scipy-notebook (BSD-3-Clause).
Includes python-lsp-server and Visual Python Widget
under their respective open-source licenses.


## Base Image

This Docker image is based on:

beclab/jupyter-scipy-notebook:notebook-7.0.6  
Copyright © BeCLab  
Licensed under the BSD 3-Clause License.


## Additional Software

This image includes additional software components:

- python-lsp-server (MIT License)
- LSP-related plugins (MIT/BSD Licenses)
- Visual Python Widget (MIT/BSD License)


# Disclaimer

This Docker image is provided “as is”, without warranty of any kind.
Use at your own risk.

The authors assume no responsibility for any damage or data loss
resulting from the use of this image.


All additional components are distributed under their
respective open-source licenses.
