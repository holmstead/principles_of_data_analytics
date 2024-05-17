# An Exploration of the Palmer Penguins Dataset

This repository contains an analysis of the Palmer Penguins dataset.[1] Horsts repo can be found here.[2] A nicely formatted copy of the dataset can be found in [UCIs machine learning archives](https://archive.ics.uci.edu/dataset/53/iris).

Several popular data-analysis libraries are used herein in an attempt to extract some [information](https://en.wikipedia.org/wiki/Information#) out of the dataset. To do so, we should approach the task with a question already in mind. Without a question, it may be difficult to extract any meaningful informatioon from a dataset. 

The program was written in Python using [VSCode](https://code.visualstudio.com/), a free open-source Integrated Development Environment (IDE).

Several libraries were used that are not part of the Python Standard Library and must be downloaded seperately. Instructions on how to install these libraries can be found in the Get Started section.


## Quickstart

 <a target="_blank" href="https://colab.research.google.com/github/holmstead/principles_of_data_analytics/blob/main/penguins.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Link generated using [Openincolab](https://openincolab.com/)


## About

Python is a general purpose programming language.

The programs/scripts in this repo were written using VSCode, a free open-source Integrated Development Environment (IDE).

In a couple of the tasks [libraries](https://realpython.com/lessons/scripts-modules-packages-and-libraries/) were used that are not part of the Python Standard Library and must be downloaded seperately. Instructions on how to install these libraries can be found in the Get Started section.

There is an online repository called the Python Package Index (PyPI) which helps find and install packages developed by the Python community.

- https://pypi.org/

More information about the libraries used in this analysis can be found below:

1. Pandas
    - https://pandas.pydata.org/

2. NumPy
    - https://numpy.org/

3. Matplotlib
    - https://matplotlib.org/

4. Seaborn
    - https://seaborn.pydata.org/


## Repo Contents

1. `palmerpenguins_dataset.csv`
   
   A dataset containing information about the palmer penguins in comma separated variables (csv) format.

2. `penguins.ipynb`

   A jupyter notebook containing an analysis of the palmer penguins dataset using pandas, matplotlib, and seaborn libraries.



## Get Started

If you dont want to run the notebook in Google CoLab you can follow these instructions to install everyhting on your machine.

The Python interperter can be downloaded [here](https://www.python.org/downloads/). 

Download VSCode [here](https://code.visualstudio.com/download).

Install the required libraries using the following command:

```
python pip install matplotlib numpy pandas seaborn notebook
```

Clone the repository:

```
git clone https://github.com/holmstead/principle_of_data_analytics.git
```

Once everything is installed and the repository cloned, you can run the notebook by opening the command line and typing the following command:

```
jupyter-notebook penguins.ipynb
```



## Get Help

Python libraries Matplotlib, Pandas, Seaborn, and NumPy all have comprehensive user guides in the official docs:

- https://matplotlib.org/stable/users/index.html

- https://numpy.org/doc/stable/user/index.html

- https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html

- https://seaborn.pydata.org/tutorial.html

- https://numpy.org/doc/stable/user/index.html


Juypter Notebooks and VSCode help can be foound herer:

- https://jupyter.brynmawr.edu/services/public/dblank/Jupyter%20Notebook%20Users%20Manual.ipynb

https://code.visualstudio.com/docs/introvideos/basics


## References

[1] Horst, Allison Marie, Alison Presmanes Hill, and Kristen B Gorman. 2020. Palmerpenguins: Palmer Archipelago (Antarctica) Penguin Data. https://doi.org/10.5281/zenodo.3960218.

[2] https://github.com/allisonhorst/palmerpenguins


## Author

M. Holmes, 2024

holmstead@protonmail.com