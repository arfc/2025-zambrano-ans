# UIUC energy model project
A model detailing the energy systems mix employed at UIUC will be simulated using [osier](https://github.com/arfc/osier). Single and multiple objective scenarios will be used. Model will be used to write an abstract for the ANS conference. osier was developed by [Sam Dotson](https://github.com/samgdotson)


## Installation of necessary packages

### Installation of osier via PyPI

`osier` can be downloaded through [PyPI](https://pypi.org/project/osier/). It can be downloaded by running the following command in the terminal:

```bash
python -m pip install osier
``` 

### Installation of osier via forking
Additionally, the associated github [repository](https://github.com/arfc/osier) can be forked and built using the terminal. The following commands can be used to fork and build using the terminal:

```bash
git clone https://github.com/arfc/osier.git
cd osier
# for a basic installation
pip install .
# (Windows/Linux) to also install the documentation dependencies
pip install .[doc]
# (MacOS)
pip install .'[doc]'
```

It is recommended to build a conda environment with osier installed using Conda/Mamba. After cloning, one can run:

```bash
mamba env create  # mamba and conda are interchangeable, here
mamba activate osier-new 
```



