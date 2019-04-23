# Gender-Equality-in-CS-Publications

This repository contains scripts I used for my Bachelor Thesis research work concerning gender equality within the authors of publications in Computer Science.

## Data used

* DBLP publication data (https://dblp.uni-trier.de/)
* NamSor gender classification data (https://v2.namsor.com/NamSorAPIv2/apidoc.html)

## Repeat my research

### Prerequisites
Using the DBLP XML data and a NamSor API key (and preferably a company account) you can follow along the entire research by executing the Jupyter Notebooks yourself. Just do the following:
* Place the DBLP XML file (named "dblp.xml") in a "data" folder in your fork.
* Place a file "key.txt" in the repo folder. Copy and paste your NamSor key in there.

### Order of Notebooks
To repeat my research (and possibly verify it!), first, execute the regular Notebooks for Data Gathering and Cleaning. They are ordered with numbers and the ordering does matter - they need to be executed in the right order, otherwise you might lack data. *(Please note: I did not get further than Gathering and Cleaning yet, even though more regular Notebooks have been prepared already.)*

The regular Notebooks have test Notebooks going along where I was experimenting. They are labelled so, for example "Test_DataGatheringAndCleaning3_Gender.ipynb". They are dependend on previous regular Notebooks, in this example "Test_DataGatheringAndCleaning3_Gender.ipynb" is dependent on "DataGatheringAndCleaning2_Authors.ipynb" (which again and as you know is dependent on "DataGatheringAndCleaning1_DBLP.ipynb"). 
