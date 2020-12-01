# Double Inverted Pendulum (DIP) modelling

## Environment Setup

* Install Miniconda: https://docs.conda.io/en/latest/miniconda.html
* Install ImageMagick Display: https://imagemagick.org/script/download.php
* Navigate to where you want to store the repository
* Open terminal and execute: `git clone git@github.com:mughees-asif/dip.git`
* Install the environment requirements in the same directory through the Miniconda terminal: `pip install do-mpc`
* Open this notebook through the Miniconda terminal: `jupyter notebook`
* You should now be set-up to run this example

## Dynamics of a DIP

| Package | Purpose | Code | 
| ------------- | ------------- | ------------- |
| SymPy | Deriving the dynamics of the system | [:memo:](https://github.com/mughees-asif/dip/blob/master/dip-equations-of-motion.ipynb) |
| [do-mpc](https://github.com/do-mpc/do-mpc) | Solving the Euler-Lagrangian equations | [:memo:](https://github.com/mughees-asif/dip/blob/master/double-inverted-pendulum-do_mpc.ipynb) | 

## Sample simulations

![DIP_Example](https://raw.githubusercontent.com/mughees-asif/dip/master/media/anim_dip.gif)
------------------------------------------
![DIP_Example](https://raw.githubusercontent.com/mughees-asif/dip/master/media/dip.gif)
------------------------------------------
