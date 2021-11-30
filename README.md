# ML4Linguists
A repo of problem sheets for 'Intro to Machine Learning for Linguists' Reading Group @ University of Cambridge

## Set-up Instructions (first time)

- NOTE: This was developed using a Windows 10 OS. If there are any issues with other OSs, please open a pull request here to fix them!
- Install [Anaconda](https://www.anaconda.com/products/individual) for your operating system. This might take a while, but it is an excellent resource for all your datascience needs
- Open the command prompt (cmd)
- Type `python -V` to check that Python is installed and you are running on v3.8+
- Type `conda list` to view a list of the installed libraries you get with conda
- Clone/download this repository - NOTE: if you are going to clone the repo, make sure to open a new branch under your name!
- In the command prompt, change your directory to wherever you have stored this repo on your device. Use `cd` followed by the path to change directory
- Then run `conda env create -f ./Environment.yaml`. This will create a virtual environment called ML4Linguists and install all the relevant packages for our tutorials (this may take a while). If you want to name the environment something else, append the previous command with `-n new-env-name`
- Then run `conda activate ML4Linguists`

## Updating the environment with updates in future classes

- If you are in the virtual environment `ML4Linguists`, first run `conda deactivate` to move back to the base environment.
- Then run `conda env update -f ./Environment.yaml`, which will update anything that is required
- Then run `conda activate ML4Linguists` to enter the virtual environment

## Checking package lists

- Run `conda list` to view the installed packages

## Jupyter notebook

- Run the command `jupyter notebook` from the command-line
- This will open a jupyter notebook in your browser at the file location associated with this repository on your local device (provided you have used `cd` correctly earlier
- Click on the notebook `LinearRegression_TutorialProblemSet.ipynb`, which will open in a new tab, and begin the tutorial

## Closing the notebook

- Save and close the notebook tab
- Return to the initial jupyter notebook tab that contains the files in your directory
- Click on the quit button to kill the notebook


Any problems, email: kv301@cam.ac.uk
