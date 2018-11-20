## Project: Titanic Survival Exploration
## Udacity's Machine Learning Engineer Nanodegree
## Introduction and Foundations

### Installation

This project requires **Python ** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included

Create a conda environment `conda create -n <envname> python=3` 

and activate it
In Windows`activate <envname>` or in Mac/Linux `source activate <envname>`

Install the mentioned packages
`conda install numpy matplotlib pandas jupyter notebook`

### Code

Template code is provided in the notebook `titanic_survival_exploration.ipynb` notebook file. Additional supporting code can be found in `visuals.py`. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `titanic_survival_exploration/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook titanic_survival_exploration.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.

### Data
The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and Kaggle and can be downloaded from [Kaggle Titanic Dataset](https://www.kaggle.com/prkukunoor/TitanicDataset#titanic_data.csv)

It contains the following attributes:

**Features**
- `PassengerId`: Passenger ID (numeric)
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name (string)
- `sex` : Sex (male/female)
- `age` : Age (numeric)
- `sibsp` : Number of Siblings/Spouses Aboard  (numeric)
- `parch` : Number of Parents/Children Aboard (numeric)
- `ticket` : Ticket Number (string)
- `fare` : Passenger Fare (numeric, real number)
- `cabin` : Cabin code (string)
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)
