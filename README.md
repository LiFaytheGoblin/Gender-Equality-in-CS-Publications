# Gender-Equality-in-CS-Publications

This repository contains scripts I used for my Bachelor Thesis research work concerning gender equality within the authors of publications in Computer Science.

## Data used

* DBLP publication data (https://dblp.uni-trier.de/)
* NamSor gender classification data (https://v2.namsor.com/NamSorAPIv2/apidoc.html)

## Repeat my research

### Prerequisites
Using the DBLP XML data and a NamSor API key (and preferably a company account) you can follow along the entire research by executing the Jupyter Notebooks yourself. Just do the following:
* Place the DBLP XML file you downloaded in a "_data" folder in the root folder of your fork.
* In "01_DatGatheringAndCleaning", in "01_DBLP.ipynb", correct the name of the imported XML file.
* Place a file "key.txt" in the root of the repo folder. Copy and paste your NamSor key in there.

If you want to save pictures of graphs, additionally 
* Create a folder "_graphs" in the root folder of your fork and inside create the folders "h1", "h2", "h3", "h4", "h5", "score"

### Order of Notebooks
To repeat my research (and possibly verify it!), first, execute the regular Notebooks for Data Gathering and Cleaning ("01_DataGatheringAndCleaning"). They are ordered with numbers and the ordering does matter - they need to be executed in the right order, otherwise you might lack data. However, you do not necessarily  need to execute the code in the folders "03_01_DataQualityExploration", "03_02_DataImprovementTests", "03_04_ImprovedDataQualityExploration". Note that "03_03_DataImprovements" and "04_01_DataImprovements" are important and necessary to be executed.

Then you can move on to hypotheses tests ("02_HypothesisTests"). You can follow along or create your own hypotheses tests!

### Speed
Some things like the parsing of XML are slow or do not work at all on some computers. I suspect it's because of the amount of RAM. It worked fine on my computer, but not on a smaller laptop I tried it with. Sorry, it was not my priority to make this faster. Make a pull request if you fix this :D

### Used my code? Questions?
Feel free to send me feedback and questions!