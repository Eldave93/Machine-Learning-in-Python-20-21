# Machine Learning in Python (Weeks 8-11)

Welcome to materials for Weeks 8-11 of Machine Learning in Python (MATH11205), a Postgraduate Course in the School of Mathematics at the University of Edinburgh.

## Viewing Notes and Exercises
If you want to view the Notes **online**, you can just follow the links below:

__SVM__

1. Maximal Margin Classifiers [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21//Week_08_SVM/1_Maximal_Margin_Classifiers.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_08_SVM/1_Maximal_Margin_Classifiers.pdf" title="PDF">PDF</a>]
2. Support Vector Machines [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_08_SVM/2_Support_Vector_Machines.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_08_SVM/2_Support_Vector_Machines.pdf" title="PDF">PDF</a>]
3. Applications [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_08_SVM/3_Applications.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_08_SVM/3_Applications.pdf" title="PDF">PDF</a>]

Exercises [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_08_SVM/SVM_Exercises.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_08_SVM/SVM_Exercises.pdf" title="PDF1">PDF1</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_08_SVM/SVM_Exercises_Answers.pdf" title="PDF2">PDF2</a>]

__Trees__

1. Decision Trees [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_09_Trees/1_Decision_Trees.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_09_Trees/1_Decision_Trees.pdf" title="PDF">PDF</a>]
2. Ensemble Averaging [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_09_Trees/2_Ensemble_Averaging.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_09_Trees/2_Ensemble_Averaging.pdf" title="PDF">PDF</a>]
3. Applications [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_09_Trees/3_Applications.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_09_Trees/3_Applications.pdf" title="PDF">PDF</a>]

Exercises [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_09_Trees/Trees_Exercises.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_09_Trees/Trees_Exercises.pdf" title="PDF1">PDF1</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_09_Trees/Trees_Exercises_Answers.pdf" title="PDF2">PDF2</a>]

__Clustering__

1. K-Means [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_10_Clustering/1_K_Means.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_10_Clustering/1_K_Means.pdf" title="PDF">PDF</a>]
2. Hierarchical and Density Clustering [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_10_Clustering/2_Hierarchical_and_Density_Clustering.html" title="HTML">HTML</a>]
3. Applications [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_10_Clustering/2_Hierarchical_and_Density_Clustering.html" title="HTML">HTML</a>]

Exercises [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21/Week_10_Clustering/3_Applications.html" title="HTML">HTML</a>]

__Ethics__

1. Big Data, Black Boxes, and Bias [Work in Progress]

If you want to download and view them **offline**, you can right click on the links above, and click "save link as". 

### HTML
- .html files can be opened using any web browser (I use chrome).
- For the notes, code can be viewed or hidden using the "Toggle Code" button at the top of the notebook.
- For the exercises, answers can be viewed or hidden by clicking "Click here for answer" under each question.

### PDF
- Notes do not display code for ease of reading.
- For the exercises, `PDF1` are just the questions, and `PDF2` are the questions and answers.
- They are useful for adding your own notes to.
- The best method I've found so far is to manually use https://pdfcrowd.com/ for converting the .html files.
	- They have a Python API... but it costs money so I do it manually.

## Running the Juypter Notebooks [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Eldave93/Machine-Learning-in-Python-20-21/HEAD)

If you want to run the Juypter Notebooks on the **cloud**, the easiest method is to click the "Launch Binder" button above.
- It make take a little bit to copy and install everything when you first get it set up, so its a good time to make a cup of tea.
- Once working, the scripts are relatively quick to run.

If you want to run them **locally**, then the way I set them up is the following (other methods exist):

1. Download Anaconda (https://www.anaconda.com/products/individual)
2. Using the "Anaconda Navigator", click on the "Environments" tab, then "Create" to make a new Python 3.8 environment (I called mine "mlp")
3. Click on the "Home" tab, on the top dropdown menu ("Applications on") select your new environment.
4. Install "Jupyter Notebook" in your environment and click "Launch".
5. Locate to where the course materials are (You could clone the repository from GitHub), and run the "package_install" notebook from the "Extra" folder. 

### Viewing Slides

I use "Rise" slideshows to present the .ipynb Juypter Notebooks. 

- If "Rise" is installed, slideshow mode can be toggled on using the barchart icon on the top toolbar in Jupyter, and off again using the x in the top left.
- You may need to zoom in and out to get some of the slides to be displayed fully, but if using Chrome then you can just toggle `CTRL +` and `CTRL -`
- To get the "Toggle code" button to work, you need to go into "File", and click "Trust Notebook".

## GitHub File Structure

You can also access the material directly though GitHub. In each of the weekly content folders you will find the following types of files:

- .ipynb: The Juypter Notebook used to create the slides and notes.
- .html: The html version of the notes and exercises.
- .pdf: A pdf version of the notes and exercises.
- .slides.html: A html version of the slides.

For each week, there are also subfolders for "Images", saved "Models", and "PDF_Prep" (files used to prepare pdfs).

As well as the weekly folders, there are folders for the "Data" used in the lectures and an "Extra" folder, containing additional material (most are currently unfinished).

## Known Issues

- .slides.html has an issue with figures not being displayed properly.
	- Its better to run using "Rise" slideshow in Jupyter.
