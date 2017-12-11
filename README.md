# CompClub-sklearn
Intro to sklearn for Comp Club

To install the AllenSDK, see this [gist](https://gist.github.com/valentina-s/0549be1dc47b3348fdfee077f260ca08) or see the instructions on Allen's website: http://alleninstitute.github.io/AllenSDK/install.html. The AllenSDK only works for python2.7 at the moment.

First, make sure you have anaconda or miniconda installed. I'd recommend [miniconda](https://conda.io/miniconda.html) since it's quicker to install.

Second, clone the repo, then install all the requirements in a new conda env by typing `conda env create -f environment.yml`.

Then, run `source activate allen` to activate the environment and `jupyter notebook` to run these notebooks.

Or, click the binder link below to run the notebooks remotely!
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dhb2128/CompClub-sklearn/docker)

If you'd prefer to use a virtuenv you can also install the dependencies using `pip install -r requirements.txt`.