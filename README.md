# Code for the paper "Apportionment with Weighted Seats"

This is the code used to run the experiments for the Bundestag Case Study section in the paper titled "Apportionment with Weighted Seats"..

## Repository structure.

Here are some details on the contents of this repository.

`main.py` - This is the script to run the experiments.

`rules.py` - This contains the implementation of the WSAMs.

`experiment.py` - This contains methods related to the experiments such as checking the satisfaction of proportionality properties, parsing Bundestag committee election data from the `bundestag_committees' folder, etc.

`election.py` - This contains the methods to calculate the various quota values for parties.

`experiment_results` - This is a folder that contains the text file (titled "results.txt") that contains the summarised results of the experiments.

`bundestag_committees` - This is a folder that contains the Bundestag committee election data that was used in the experiments.

`README.md` - This is the README file.

## How to run the experiments

Run the main script with the following command (experiments coded using Python3):

	python3 main.py

The results can then be read in the `results.txt` file which can be found in the `experiment_results` folder.

Note that the following must be installed to run the experiments:

- The `mip' package (https://pypi.org/project/mip/).
- The `numpy' package (https://pypi.org/project/numpy/).
