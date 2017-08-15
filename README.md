# deep-learning-bike-sharing
This is a project made to create a neural network from scratch.
It's based on [Udacity's Deep network nanodegree project](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101).

## What is this about
This is about creating a neural network that will be able to predict the bike renting rate over a period of time based on past data.

Data is coming from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)

Actual data is coming from a real bike rental company called [Capital Bikeshare](https://www.capitalbikeshare.com/) who is [sharing its data](https://www.capitalbikeshare.com/system-data)

## project overview

If you are just interested in the theory, you can view my [full project report here](https://github.com/fdagosti/deep-learning-bike-sharing/blob/master/Your_first_neural_network.ipynb). Else, you can install the whole environment if you want to play with the data as well

## Installing the environment
The whole projects run under a [Jupyter notebook](http://jupyter.org/)

you'll need to install [Anaconda](https://www.continuum.io/) to get dedicated environments running the experiments

once you have installed anaconda, install the needed dependencies:
```bash
conda create --name bike-share python = 3
source activate bike-share
conda install numpy matplotlib pandas jupyter notebook
```

then run the following to open the notebook server:
```bash
jupyter notebook
```

in your browser, open `dlnd-your-first-neural-network.ipynb`

Then play around in the notebook. Happy hacking !!

