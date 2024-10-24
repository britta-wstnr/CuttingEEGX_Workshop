# Material for the MNE-Python workshop at CuttingEEGX 2024

More info on the workshop [on the CuttingEEGX web page](https://cuttingeegx.org/registration/#Nijmegen)

Authors of the material:

	- Britta Westner, RadboudUMC Nijmegen, Donders Institute
    - Tilman Stephani, Radboud University Nijmegen, Donders Institute

## Before you arrive

Please make sure you do the following steps before the first hands-on session:

0. You will need to download this directory of scripts.
1. You will need to have an up-to-date version of MNE-Python installed on your machine (you need a *full install* with all dependencies, **not** "MNE-Python with core functionalities only"). See instructions at: https://mne.tools/stable/install/index.html. You can either use the standalone installers or you can use `conda`. Do not use `pip`, as this will not give you a full install with all dependencies. The current version number is 1.8.0 or higher.
2. You will need to check your installation. For that, please look at the (very short!) notebook [Check your installation](Installation_check.ipynb). See below if you need a reminder how to start it.
3. If you are not too familiar with MNE-Python yet, we invite you to take the time to work on some tutorials. See below for some recommendations.

### Start a Jupyter notebook

To start a Jupyter notebook, open your terminal and navigate to the directory where you saved this directory of scripts. If you use `conda`, make sure you are in the environment that has the full installation of MNE-Python as specified in the first point in the list above.  
Then type the command `jupyter notebook` and Jupyter should open in your internet browser. Click on the notebook you want to run!

### If you want to refresh your knowledge

We will work on source reconstruction during the workshop. To get the most out of this, you should be familiar with topics like reading in data, pre-processing, epoching, and averaging. We will not cover these topics during the workshop.
If you need a refresher of those topics, we recommend the tutorials on the MNE-Python homepage.  
Example tutorials include:
- [Reading data from different systems](https://mne.tools/stable/auto_tutorials/io/index.html)
- [Data cleaning](https://mne.tools/stable/auto_tutorials/preprocessing/10_preprocessing_overview.html)
- [EEG referencing](https://mne.tools/stable/auto_tutorials/preprocessing/55_setting_eeg_reference.html)
- [Epoching data](https://mne.tools/stable/auto_tutorials/epochs/10_epochs_overview.html)
- [Averaging epochs](https://mne.tools/stable/auto_tutorials/evoked/10_evoked_overview.html)

### References and credit

The material in this directory was created by Britta Westner with help from Tilman Stephani. Parts of the material draw on MNE-Python tutorials which were created by various MNE-Python contributors. Other parts are inspired by the Practical MEEG workshops from 2022 and 2020. The material for those was created by Alexandre Gramfort, Denis A. Engemann, and Britta Westner.

The MNE software when used in publications should be acknowledged using citations.

To cite MNE-C or the inverse imaging implementations provided by the MNE software, please use:

	A. Gramfort, M. Luessi, E. Larson, D. Engemann, D. Strohmeier, C. Brodbeck, L. Parkkonen,
	M. Hämäläinen, MNE software for processing MEG and EEG data, NeuroImage, Volume 86,
	1 February 2014, Pages 446-460, ISSN 1053-8119.

To cite the MNE-Python package, please use:

	A. Gramfort, M. Luessi, E. Larson, D. Engemann, D. Strohmeier, C. Brodbeck, R. Goj, M. Jas,
	T. Brooks, L. Parkkonen, M. Hämäläinen, MEG and EEG data analysis with MNE-Python,
	Frontiers in Neuroscience, Volume 7, 2013, ISSN 1662-453X.

We also encourage users to cite the _used version_ of the software, to give credit to all contributors.