# BrainStain.ai :brain:

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) <a href="https://postgresql.org"><img src="https://img.shields.io/badge/Powered%20by-PostgreSQL-blue.svg"/></a>

Brain tumor detector using U-NET architecture and Sorensen Dice Index metric. Trained on [3D NIfTI data](https://www.med.upenn.edu/cbica/brats2020/data.html). 

<img src="header.gif">

## Dependencies

| Package           | Tested version |
|--------------------|----------------|
| tensorflow         | 2.11.0         |
| keras              | 2.10.0         |
| opencv_python      | 4.7.0.68       |
| nibabel            | 5.0.1          |
| numpy              | 1.23.3         |
| pandas             | 1.5.0          |
| matplotlib         | 3.6.0          |
| scikit_learn       | 1.2.2          |
| SimpleITK          | 2.2.1          |
| ipython            | 8.11.0         |



## Installation

Install my-project with npm.

```bash
  $ git clone https://github.com/yaashwardhan/BrainStain.ai.git
```
Navigate to the project directory.
```bash
  $ cd BrainStain.ai/
```
Create a new Conda environment.
```bash
  $ conda create --name environment-name python=3.10.10
```
Note: Replace environment-name with the name you want to give your Conda environment.

Activate the newly created environment.
```bash
  $ conda activate environment-name
```
Install the project dependencies from the requirements.txt file.
```bash
  $ pip install -r requirements.txt
```
Verify that all the required packages have been installed correctly by running:
```bash
  $ pip freeze
```
