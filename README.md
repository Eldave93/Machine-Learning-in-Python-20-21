[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Eldave93/Machine-Learning-in-Python-20-21/HEAD)
# Machine Learning in Python (Weeks 8-11)

**File Explanation**

In each of the folders you will find the following types of files:

- .ipynb: The Juypter Notebook used to create the slides and notes.
- .html: The html version of the notes.
	- Code can be viewed or hidden.
- .slides.html: A html version of the slides.
	- Has an issue with figures not being displayed properly.
    - Its better to run using "Rise" slideshow in Jupyter.

There are also folders for "Data" and "Images", as well as saved "Models".

**Setup**
If you want to see the slides as presented, or run the .ipynb on the cloud, the easiest method is to click the "Launch Binder" button at the top of the page.

I use "Rise" slideshows in my lectures. This can be toggled using the barchart icon on the top toolbar in Jupyter.

- You may need to zoom in and out to get some of the slides to be displayed fully, but if using Chrome then you can just toggle `CTRL +` and `CTRL -`

If you want to run them locally, then the way I set them up is the following (other methods exist):

1. Download Anaconda (https://www.anaconda.com/products/individual)
2. Using the "Anaconda Navigator", click on the "Environments" tab, then "Create" to make a new Python 3.8 environment (I called mine "mlp")
3. Click on the "Home" tab, on the top dropdown menu ("Applications on") select your new environment.
4. Install "Jupyter Notebook" in your environment and click "Launch".
5. Locate to where the course materials are (maybe you used git to pull the repository from GitHub), and run the "package_install" notebook

Now you are free to run the materials. As long as you use the Anaconda environment to run them it should work. 

**Notes**
- .html was chosen over .pdf as if found .pdf conversions had a number of errors:
	- Has an issue with numbering titles.
	- Doesn't display tables as well as the html version.
	- Cannot use \begin{align} in markdown math.
- IPyPublish is something to look into for the future

- https://www.markroepke.me/posts/2019/06/05/tips-for-slideshows-in-jupyter.html
