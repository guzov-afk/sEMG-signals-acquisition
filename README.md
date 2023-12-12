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

# LoadData Module

This module provides functionality for loading and preprocessing data for arm and leg movement classes.

## Constructor

### `__init__(self, dataDirectory)`

Initializes the object and sets the data directory.

## Data Loading Methods

### `load_data(self, filename)`

Loads data from a file specified by the filename parameter using the `np.load` function from NumPy.

### `loadData_armthreeClasses(self)`

Loads data for three different arm classes. Extracts channels and adds them to dataStore along with corresponding labels.

### `loadData_twoClasses_leg(self)`

Loads data for two classes related to leg movements. Divides the data into two time intervals.

### `loadData_twoClasses_firstarmmovement(self)`

Loads data for two classes related to the first arm movement. Divides the data into two time intervals.

### `loadData_twoClasses_secondarmmovement(self)`

Loads data for two classes related to the second arm movement. Divides the data into two time intervals.

### `loadData_twoClasses_thirdarmmovement(self)`

Loads data for two classes related to the third arm movement. Divides the data into two time intervals.

## Usage

Include an example or describe how to use these methods in your project.

```python
from loaddata import YourDataLoader

# Initialize the data loader
data_loader = YourDataLoader("your_data_directory")

# Load data for three arm classes
data_loader.loadData_armthreeClasses()

# Load data for two leg movement classes
data_loader.loadData_twoClasses_leg()

# Load data for two classes related to the first arm movement
data_loader.loadData_twoClasses_firstarmmovement()

# Load data for two classes related to the second arm movement
data_loader.loadData_twoClasses_secondarmmovement()

# Load data for two classes related to the third arm movement
data_loader.loadData_twoClasses_thirdarmmovement()
