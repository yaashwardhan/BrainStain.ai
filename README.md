# BrainStain.ai :brain:


[![Up to Date](https://github.com/yaashwardhan/BrainStain.ai/workflows/Up%20to%20Date/badge.svg)](https://github.com/yaashwardhan/BrainStain.ai/actions?query=workflow%3A%22Up+to+Date%22)


Brain tumor detector using U-NET architecture and Sorensen Dice Index metric. Trained on 3D NIfTI data. 

<img src="header.gif">

## Dependencies

| Package                                   | Tested version |
|-------------------------------------------|----------------|
| [NumPy](http://www.numpy.org/)            | 1.14.2         |
| [NiBabel](http://nipy.org/nibabel/)       | 2.2.1          |
| [matplotlib](http://matplotlib.org/)      | 2.2.0          |
| [imageio](https://imageio.github.io/)     | 2.2.0          |
| [scikit-image](https://scikit-image.org/) | 0.13.0         |

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
