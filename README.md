# Machine Learning in Python (Weeks 8-11)

Welcome to materials for Weeks 8-11 of Machine Learning in Python (MATH11205), a Postgraduate Course in the School of Mathematics at the University of Edinburgh.

## Viewing Notes
If you want to view the Notes **online**, you can just follow the links below:

__SVM__

1. Maximal Margin Classifiers [<a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21//Week_08_SVM/1_Maximal_Margin_Classifiers.html" title="HTML">HTML</a>, <a href="https://github.com/Eldave93/Machine-Learning-in-Python-20-21/blob/master/Week_08_SVM/1_Maximal_Margin_Classifiers.pdf" title="PDF">PDF</a>]
2. <a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21//Week_08_SVM/2_Support_Vector_Machines.html" title="Support Vector Machines">Support Vector Machines</a>
3. <a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21//Week_08_SVM/3_Applications.html" title="Applications">Applications</a>

__Trees__

- Work in Progress

__Clustering__

- Work in Progress

__Ethics__

- Work in Progress

If you want to download and view them **offline**, you can right click on the links above, and click "save link as". 

### HTML
- .html files can be opened using any web browser (I use chrome).
- Code can be viewed or hidden using the "Toggle Code" button at the top of the notebook.

### PDF
- They do not display code.
- They are useful for adding your own notes to.
- .pdf conversions can have some issues:
	- Numbering titles.
	- Doesn't display tables as well as the html version.
	- Some issues with \begin{align} in markdown math.

## Viewing Exercises

If you want to view the Exercises **online**, you can just follow the links below:
- <a href="https://Eldave93.github.io/Machine-Learning-in-Python-20-21//Week_08_SVM/SVM_Exercises.html" title="SVM Exercises">SVM Exercises</a>

If you want to view them **offline**, then follow the same instructions as above for the Notes.

- Exercise answers can be viewed or hidden by clicking "Click here for answer" under each question.

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
- .slides.html: A html version of the slides.

For each week, there are also subfolders for "Images" and saved "Models".

As well as the weekly folders, there are folders for the "Data" used in the lectures and an "Extra" folder, containing additional material (most are currently unfinished).

## Additional Notes

- .html was chosen over .pdf as I found .pdf conversions had a number of errors:
	- Has an issue with numbering titles.
	- Doesn't display tables as well as the html version.
	- Cannot use \begin{align} in markdown math.
- .slides.html has an issue with figures not being displayed properly.
	- Its better to run using "Rise" slideshow in Jupyter.
