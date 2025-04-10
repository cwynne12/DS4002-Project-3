# DS4002-Project-3
## Section 1: Software and Platforms
Software: We used Google Colab to perform EDA and CNN analysis 
* Packages used: pandas, numpy, matplotlib, CV2 to conduct our intial preprocessing and EDA. ImageDataGenerator from tensor flow was used to run the CNN analysis.
* Platform: All members used Macs

## Section 2: Map of Our Documentation 
This repository contains:
* LICENSE
* README.MD
* REFERENCES File
* DATA Folder
  * Link to Google Drive with Image Data 
* SCRIPTS
  * EDA + ANALYSIS Script (DS 4002 Project 3 Code.ipynb)
* OUTPUT
  * Data dictionary (DATA DICTIONARY.pdf)
  * EDA Plots (EDA PLOTS.pdf)
  * Analysis Results and Final Plots (ANALYSIS PLOT + RESULTS.pdf)

## Section 3: Instructions for Reproducing Our Results
1. Open “DS 4002 Project 3 Code.ipynb” script in Google Colab (file found in SCRIPTS folder in Github).
2. Download tomatoes dataset in DATA folder: click Google Drive link and download the files in the four folders.
3. Run “PART 1: EDA” in "DS 4002 Project 3 Code.ipynb" Python script
* Create 4 folders in left margin under 'sample_data" in Google Colab (call them: damaged, old, ripe, unripe)
* Read in tomato data
* Import any necessary packages
* Run 5 eda plots
4. Run “PART 2: CNN Analysis” in "DS 4002 Project 3 Code.ipynb" Python script
* Create 1 folder called "tomatoes" under sample_data in Google Colab in left margin. Put the already existing folders (damaged, old, ripe, unripe) into tomatoes folder.
* Run script to build CNN model, test model accuracy, and generate final results table
