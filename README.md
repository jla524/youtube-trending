# youtube-trending
YouTube is a world-famous video-sharing website. As a student who consumes YouTube videos every day, for educational and entertainment purposes, I want to understand how the algorithm for selecting trending videos works.


## Instructions to run the notebook

1. Clone this repository

2. Download the dataset from Kaggle at:
https://www.kaggle.com/datasnaek/youtube-new

    Unzip the dataset, rename it "data", and move it into your local repository.
    
    For example:
    `mv ~/Downloads/4549-466349-bundle-archive/ data/`

3.  Create and activate a virtual environment (optional)

    with [Pip](https://pip.pypa.io/en/stable/):
    
    `python3 -m venv youtube_trending_env`
    
    `source youtube_trending_env/bin/activate`
    
    with [Anaconda](https://www.anaconda.com/distribution/):
    
    `conda create -n youtube_trending_env python=3.7`
    
    `conda activate youtube_trending_env`

4.  Install the required Python libraries 

    with [Pip](https://pip.pypa.io/en/stable/):
    `pip install -r requirements.txt`
    
    with [Anaconda](https://www.anaconda.com/distribution/):
    `conda install -r requirements.txt`
    
5.  Install an ipython kernel for the virtual environment (optional)

    `pip install ipykernel`
    
    `python3 -m ipykernel install --user --name=youtube_trending_env`
    
    You may need to create a new notebook with this environment and copy the content from youtube.ipynb.
    
6.  Start Jupyter Notebook using the command `jupyter-notebook`

    In the new browser tab, click on youtube.ipynb, the fast forward button, and "Restart and Run All Cells".
