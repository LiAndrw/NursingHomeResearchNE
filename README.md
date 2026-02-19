# ObesityResearchNE
 Analysis of correlations between obesity, mortality, and comorbilities. You only really need to know about/care about 5 files/folders

## environment.yml
This file (hopefully) contains all of the necessary imports and software for running my code. To use it, do the following after cloning and then navigating into this repository on your personal device:

```
conda env create -f environment.yml
```

That should download all of the necessary imports and software.

## MDS Sample.csv
There are 4 original datasets in this repository, but the most recent and cleaned one (and the one I used in my code) was MDS sample.csv. The others are either in a form I don't particularly like using (.txt) and/or are older and lack certain info/features (MDS_sample.csv). 

## final_code.ipynb 
To run, make sure to first install all relevant imports, then just run all of the cells in final_code.ipynb. If using VSCode, all you should need to do is go to the final_code.ipynb file and hit the "Run all" button (top center). All of my code contains comments explaining everything, but if you are confused by something then please notify me.
 
## testing_notebook.ipynb
Contains EDA/early code that I used to better understand the data. I later moved all of the important code to final_code.py

## Visualizations_and_Tables
All of the figures and tables I created in final_code.ipynb are also contained in this folder (in .png form for the heatmaps, .csv for everything else).



