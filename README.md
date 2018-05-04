# KKBOX CHURN CHALLENGE

This is a project carried out for the course **CE4041, Machine Learning**, in Nanyang Technological University (Singapore) for Semester 2 2017/18.

The project consists in predicting if a user makes or does not make (churn) a new service subscription transaction in a streaming music online platform (KKBOX) within 30 days after the membership expiration date for that user.

To do this project we used Jupyter Notebooks under Python 3.6.
![alt text](https://www.python.org/static/community_logos/python-logo-inkscape.svg)

## Developer's guide

 1. **Data exploration**'s notebooks are stored at `.\Data Exploration` directory. There are 3 files for each of the datasets: _transactions_, _user logs_ and _members_. Inside this directory there is a file called `Loading_user_logs_FINAL.ipynb` that is used to load all the _user logs_ data (around 30GB).
 2. **Feature Engineering**'s notebooks are stored at `.\Feature Engineering` directory. 
 3. Notebooks for the training and testing of our **model** are stored at `.\Prediction Model` directory. 

## Get started
Installing Python and its libraries is generally easy. The installation process is shown below for Windows and Mac OS.

First of all check that you don't already have Python installed by entering _python_ in a command line window. If it is already installed, it will show Python version.

### For Windows

 1. Download and install Python 3.6 with the `.exe` file from [here](https://www.python.org/downloads/windows/).
 2. Download and install Anaconda (package that contains Jupyter Notebooks) from [here](https://www.anaconda.com/download/#windows).
 3. Launch Anaconda from Windows Start Menu.
 4. Open Jupyter Notebooks and go to the folder where you have your Jupter Notebook's files.
 
### For Mac

 1. Download and install Python 3.6 with the by typing `.pkg` fie from [here](https://www.python.org/downloads/mac-osx/).
 2. Download and install Jupyter Notebooks by typing into the terminal:
    `python3 -m pip install --upgrade pip`
    `python3 -m pip install jupyter`
 3. Launch **Terminal** and type `jupyter notebook`.
 4. Once Jupyter Noteboo is open, browse to the folder where you have your Jupter Notebook's files.
 
## Libraries used
The following libraries are needed: `numpy`, `pandas`, `time`, `sklearn`, `xgboost`, `matplotlib`, `mpld3`, `seaborn` and `datetime`.

Note that some of them are installed together with either _Anaconda_ or _Jupyter Notebook_.

## Results
We achived **TOP 8.5%** with a Kaggle private result (log loss) of **0.11859**.
![log_loss_score.png](https://cdn1.imggmi.com/uploads/2018/5/1/c8cc8f1304a1eaf71dab107d6e3f7e16-full.png)

## Group members

 - Pablo Javier de Paz Carbajo
 - Rick Schneider
 - Maxime Kayser
 - Ragnhild Skirdal Froehaug
 - Martha Honganvik Andersen

## Other useful links

 - [Python oficial website](https://www.python.org/).
 - [Python 3.6 documentation](https://docs.python.org/3/).
 - [Anaconda documentation](https://docs.anaconda.com/anaconda/).
 - [Jupyter Notebooks documentation](http://jupyter.org/install).
