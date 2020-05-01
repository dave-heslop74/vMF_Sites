## Welcome to vMF_Sites
This repository contains the *vMF_Sites* package, which was created to accompany the publication:

D. Heslop & A. P. Roberts (2020). Uncertainty propagation in hierarchical paleomagnetic reconstructions. *Journal of Geophysical Research (Submitted)*.

The package provides Python (v3.7) code and an interactive notebook to perform uncertainty propagation when averaging Fisher (1953) distributions, such as those that are used to represent paleomagnetic site mean directions. 

### Running on the Cloud
The simplest way to run the calculation notebook is on the Binder cloud, using this button: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dave-heslop74/vMF_Sites/master?urlpath=%2Fapps%2FvMF_Sites.ipynb)

There is a short YouTube tutorial <a href="https://youtu.be/ecHZxUA6-Yg" target="blank">here</a>.

### Running locally
The *vMF_Sites* package can be installed locally using the ```pip``` command:

```pip install git+https://github.com/dave-heslop74/vMF-Specimens.git```

Package dependencies can be found in the ```requirements.txt``` file included in this repository and the ```postBuild``` file provides commands to setup the interactive notebook.

An example notebook ```vMF_Sites.ipynb``` is contained in this repository and demonstrates how the package can be used.
