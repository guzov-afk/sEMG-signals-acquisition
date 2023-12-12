# sEMG-signals-acquisition


Brief description of the script and its purpose.

## Requirements

- Python 3.x
- PyQt5
- pyqtgraph
- numpy

## Installation

1. Clone the repository:

```bash
git clone https://github.com/guzov-afk/sEMG-signals-acquisition.git
cd sEMG-signals-acquisition


## Run the script using Python


python sEMG_signals_acquisition.py


## Load Data

1. Constructor:

__init__(self, dataDirectory): Initializes the object and sets the data directory.

2. Data Loading Method:

 load_data(self, filename): Loads data from a file specified by the filename parameter using the np.load function from NumPy.

3. Method for Loading Data with Three Arm Classes:

loadData_armthreeClasses(self): Loads data for three different arm classes. Extracts channels and adds them to dataStore along with corresponding labels.

4. Method for Loading Data with Two Leg Movement Classes:

loadData_twoClasses_leg(self): Loads data for two classes related to leg movements. Divides the data into two time intervals.

5. Method for Loading Data with Two Classes for First Arm Movement:

loadData_twoClasses_firstarmmovement(self): Loads data for two classes related to the first arm movement. Divides the data into two time intervals.

6. Method for Loading Data with Two Classes for Second Arm Movement:

loadData_twoClasses_secondarmmovement(self): Loads data for two classes related to the second arm movement. Divides the data into two time intervals.

7. Method for Loading Data with Two Classes for Third Arm Movement:

loadData_twoClasses_thirdarmmovement(self): Loads data for two classes related to the third arm movement. Divides the data into two time intervals.
