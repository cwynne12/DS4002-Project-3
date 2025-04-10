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
  * EDA Script
* OUTPUT
  * Data dictionary (DATA DICTIONARY.pdf)
  * EDA Plots (EDA PLOTS.pdf)
  * Analysis Results and Final Plots (ANALYSIS PLOT + RESULTS.pdf)

## Section 3: Instructions for Reproducing Our Results
1. Open “DS 4002 Project 3 Code.ipynb” script in Google Colab (file found in SCRIPTS folder in Github)
2. Download tomatoes dataset: Import all 20 pilot show script pdfs into Google Colab (files found in DATA folder in Github)
3. Run “PART 1: Prepare data” in Python script
* Import any necessary packages (install PyPDF2 and SentimentIntensityAnalyzer)
* Extract text from PDF and save as a new Pandas data frame 
* Install and define VADER
4. Run “PART 2: EDA plot” in Python script
* For accessibility, save dataframe of produced sentiment scores as an .xlsx file (this has already been provided to you in the SCRIPTS folder and is called "all_sentiment_scores.xlsx"). This is the final data used for analysis.
* Run the three EDA plots
5. Run “PART 3: Multiple Linear Regression Analysis” in Python code
* Read in excel ("all_sentiment_scores.xlsx") and print df
* Run Multiple Linear Regression on data
* Run plot 4
