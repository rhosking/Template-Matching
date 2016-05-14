#Mental template matching as a cultural transmission mechanism

This repository contains the code and data associated with the published paper which can be found here - DOI link

###Summary
Among humans, the cumulative evolution of technologies and traditions is claimed to be dependent on our unique capabilities for teaching, language and imitation. Examples of cumulative cultural evolution in nonhuman animals are rare. However, less elaborate cognitive mechanisms might allow some forms of cultural evolution in other species. Tool-making New Caledonian crows are exceptional in that they appear to have a material culture which has diversified and incorporated incremental improvements over time. However, these crows seem to lack the capacity for imitation, teaching or language. One possibility is that their varied tool designs could be culturally transmitted if these crows acquire a mental tool template from observing their parent’s tools, and then reproduce this template in their own manufacture – a process analogous to avian song learning. If this hypothesis is correct these crows should have the capacity for mental template matching. Here, we tested whether New Caledonian crows exhibit mental template matching in a novel manufacture paradigm. Crows were first trained to drop paper into a vending machine to retrieve rewards. They later learnt that only items of a particular size (large or small templates) were rewarded. At test, despite being rewarded at random, and with no physical templates present, these crows manufactured items that matched the size of the previously rewarded templates. Thus, New Caledonian crows possess the cognitive machinery for mental template matching: a mechanism that could support the cumulative evolution of material cultures among this species and others.

###Understanding this collection

####The following describes how the data and code in this collection are organized:
* The iPython/Jupyter Notebook that runs the analysis is found in the 'Analysis Script' Folder
* The Paper scans that are the subject of the analysis are found in the 'Original Paper Scans' Folder
* The 'Scans to determine units' folder contains some images we used to calibrate the units
* The resulting data can be found in the 'Generate Data' Folder, while the processed images (showing the inferred borders and bounding boxes) can be found in the 'Processed Images' Folder, grouped in the image types.

####How to run the analysis
* Ensure you have the Jupyter notebook installed, this is best achieved by installed the Anaconda Python Environment - https://www.continuum.io/downloads
* You will also need to install OpenCV. 'conda install -c https://conda.anaconda.org/menpo opencv'
* You start the iPython/Jupyter Notebook through either the launcher icon, or through the command line by typing 'jupyter notebook'
* Once started, Juypter will open a new window/tab in your browser. From there open the 'AnalyseImages.ipynb' notebook
* To run the analysis, run through all the cells, except the last. Here you can choose which images to analyze. This is done by changing the selected folder (see inline comments) and changing the output filename (also see inline comments)
