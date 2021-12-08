# Density Learning Tutorials

To ease development, we provide a general conda environment with some of the
packages that we will use in these tutorials, then we let the user find
the PyTorch version that fits their machine requirements, and finally we install
the custom packages.

	conda create --file environment.yml 

Besides, we recomend users to install the PyTorch version matching
their system requirements. Check the [PyTorch](https://pytorch.org)
webpage to find how to install PyTorch. We tested that the PyTorch LTS
with 11.1 CUDA drivers runs OK.

The tutorial packages can be installed from the source code. We recommend to follow this 
sequence to avoid some dependencies clashes.

	pip install git+https://github.com/brunocuevas/a3md-utils.git
	pip install git+https://github.com/brunocuevas/a3md.git
	pip install git+https://github.com/brunocuevas/DeepDFT.git
	pip install pyscf == 1.7.6

To start the tutorials, we can just open a jupyter-lab session and open the notebooks.