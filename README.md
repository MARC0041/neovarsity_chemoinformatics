# neovarsity_chemoinformatics

# Chapter1-2: Setting Up

## Python virtual environments
```
# the following command does not work as there is no native build for python below 3.8 for apple silicon. -- https://github.com/conda/conda/issues/12206 
# conda create -n neovarsity python=3.7 -y
conda create -n neovarsity python=3.10 -y
conda activate neovarsity
conda config --add channels conda-forge
conda install -c rdkit rdkit
conda install -c sepandhaghighi pycm -y
conda install -c conda-forge imbalanced-learn -y
conda install molvs -y
conda install -c conda-forge padel
```

## Datawarrior
1. Visit the website www.openmolecules.org.

2. Locate the "Download" button and click on it to initiate the download process for the file compatible with your Operating System (OS). If you encounter any issues with downloading the file, please please ask for help in the Neovarsity Slack community.

3. For Windows users:

Locate the downloaded file with the extension ".msi" and perform a left double-click on it.
Follow the provided instructions to proceed with the installation.
4. For Linux users:

Open your terminal.
Execute the following command to extract the folder: tar -zxvf datawarriorXXXlinux.tar.gz
(Please note that the current version as of 15/07/2023 is datawarrior550.tar.gz)

Ensure that the file name contains **"tar.gz" **as the extension. If necessary, correct the name accordingly.
Change to the datawarrior directory by running the following command: cd datawarrior
Set the permissions for the* install.sh* file using the command: chmod 755 install.sh
Execute the installation script with administrative privileges: sudo ./install.sh
5. For macOS users:

Locate the downloaded file with the extension ".dmg" and double-click on it to mount the disk image.
Open the mounted disk image and locate the DataWarrior application.
Drag the DataWarrior application icon to the Applications folder to install it.
6. To install the program on macOS, follow these steps:

Open your Applications folder.
Locate and launch the DataWarrior application.
Follow the on-screen instructions to complete the installation process.
The program is now installed on your system. To launch the program, you can find it in your Applications folder or use Spotlight Search to locate and open DataWarrior.

We hope you find this instruction manual helpful. If you need any further assistance, please ask for help in the Slack community.

## KNIME
Here are the installation instructions for KNIME:

1. Go to the website https://www.knime.com/downloads.

2. Fill out the form with the necessary information and click on the "Download" button to download the file for your Operating System (OS).

3. For Windows users:

Locate the downloaded file and execute it.
Follow the on-screen instructions to proceed with the installation.
4. For Linux users:

Open your terminal.
Execute the following command to extract the folder: tar -zxvf knime_XXXversion.tar.gz (Please note that the current version as of 15/07/2023 is knime_4.7.5.linux.gtk.x86_64.tar.gz)
5. For Linux users, to run KNIME:

Either double-click the "knime" file in a file browser, or
Execute the "knime" command in a shell.
6. For macOS users:

Either double-click the "knime.app" file in Finder, or
Execute the following command in Terminal: /Applications/knime/knime.app/Contents/MacOS/knime
Once KNIME is launched, it will prompt you to select a workspace directory where it will store its project files.
Choose a directory for your workspace and click "OK" to proceed.
KNIME will create an empty workflow in the selected workspace, allowing you to start assembling a workflow immediately.
Please follow these steps to install and set up KNIME on your system. If you have any further questions or need assistance, please ask in the Neovarsity Slack Community.

# Chapter 3: Molecular Drawing Techniques

# Chapter 4-5: File formats and conversions
## Chemical Datasets
- SDF
- SMILES
- SMARTS
## Macromolecules
- PDB
- fasta
## Reactions
- SMARTS
- rxn
## Others
- mol dynamics trajectory - gro
- workspace environment - mrv, moe
## Conversions
- Pandastools
- knime

# Chapter 6: Data curation and standardization


# Chapter 7: Chemical search and filtering

# Chapter 8: Molecular descriptors

# Chapter 9: Maximum common substructure

# Chapter 10: Minmax diversity

# Chapter 11: Chemical similarity

# Chapter 12: Activity cliffs

# Chapter 13: molecular graphs and visualisation

# Chapter 14: clustering techniques

# Chapter 15: QSAR

# Chapter 16: chemical databases

# Chapter 17: Ring mining techniques

# Chapter 18: Structure transformations

# Chapter 19: Combinatorial library

# Chapter 20: Bioisoster shape similarity

# Chapter 21: Virtual screening



