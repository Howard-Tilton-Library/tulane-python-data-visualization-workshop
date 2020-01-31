# Tulane Introduction to Python for Data Visualization Workshop Resources
Workshop materials and data visualization resources for the __Introduction to Python for Data Visualization Workshop at Tulane University Howard-Tilton Memorial Library

[![License: MIT](https://img.shields.io/github/license/pete-lawson/tulane-python-data-visualization-workshop)](https://opensource.org/licenses/MIT)
[![GitHub Follow](https://img.shields.io/github/followers/pete-lawson)](https://github.com/pete-lawson)

**Python package dependencies:** `numpy` `pandas` `jupyter` `matplotlib` `seaborn` `plotly`. If you have installed Python through the Anaconda Python distribution then all of these packages will be installed except `plotly`. To install `plotly` run `conda install package-name` in your terminal. 

## Table of Contents

1. [Workshop Review](#review)
2. [Jupyter Notebook Resources](#jupyter)
3. [Gathering and processing data with Python](#data)
4. [Color in Data Visualization](#color)
5. [Additional Resources](#Resources)

<a name="review"/>

## Workshop Review

The first half of the workshop, including the introduction to Python, as well as plotting using the `matplotlib` library, is primarily based on the Software Carpentries workshop: [Plotting and Programming in Python](http://swcarpentry.github.io/python-novice-gapminder/). Please review lesson one (Running and Quitting) through lesson nine (Plotting) for a thorough review of the materials covered during the workshop. 

For more background in developing foundational coding and data science skills please refer to other lessons available through the Software Carpentries: https://software-carpentry.org/lessons/

<a href="https://software-carpentry.org/lessons/">
         <img alt="Software Carpentry Logo" src="carpentries.png"
         width=450">

<a name="jupyter"/>


For a review of the second half of the workshop, on plotting in Python with the `seaborn` and `plotly` libraries review the [Data Visualization in Python with Seaborn and Plotly Jupyter Notebook](https://github.com/pete-lawson/tulane-python-data-visualization-workshop/blob/master/data-visualization-in-python-with-seaborn-and-plotly.ipynb) in this Github repository. You can also download the notebook for use on your own computer. 

## Jupyter Notebook Resources 
The [Jupter Notebook](https://jupyter.org/index.html) is a an open-source, web-based application that can be run locally, or shared online, and allows you to create and share documents (notebooks) that contain live code, visualizations, narrative text, and mathematical equations. They provide a wonderful way of documenting and sharing your research with the world. 

### Sharing your Jupter Notebook. 
These notebooks are rendered natively in Github so you can share them with others. They can be managed under versioning control using Git, and shared on [GitHub](https://github.com/), a cloud-based hosting service that allows you to manage and share your Git repositories. For more information on versioning control and how to create a Git project and share it with the world follow the [Software Carpentries tutorial on Version Control with Git and Github](http://swcarpentry.github.io/git-novice/).
<a name="color"/>

### Jupyter Notebook Shortcuts
To see a list of keyboard shortcuts, in a running Jupyter notebook first enter command mode by hitting `esc`. Then press the `h` key to display the help menu, which will display common operations and their corresponding shortcuts. These shortcuts are operating system dependent, so if you call the `h` prompt from Windows your shortcuts will look different than if you call `h` from a Mac.

### Jupyter Notebook Plugins
Jupyter is extensible, that is you can add extensions to it in order to enhance its functionality. One such extension is the [RISE](https://rise.readthedocs.io/en/maint-5.6/) extension. __RISE__ stands for __Reveal.js -- Jupyter/IPython Slideshow Extension__. This extension allows you to toggle between a normal notebook instance and an interactive presentation mode. The introduction to Data Visualization presentation at the beginning of the workshop was simply a Jupyter Notebook in RISE mode. 

[![Reveal.js](https://miro.medium.com/max/500/0*7l6Q6WgP4_DN_VLI.png)](https://rise.readthedocs.io/en/maint-5.6/)

#### Installing RISE
To install RISE run `conda install -c conda-forge rise`. You may notice some additonal commands then the normal `conda install some-package`. This is because the extension we want to install (RISE) is not an offical extension, but instead developed by the community. To install extensions developed by the community we need to specify the community built distribution channel `conda-forge` using the `-c` argument to indicate that we are using an alternative package channel. Once installed, to enable RISE mode while in a running Jupyter Notebook instance use the keyboard shortcut `Alt-r`. 

## Color in Data Visualization

The essential tool for selecting color maps is [ColorBrewer](http://www.colorbrewer2.org)

[![Color Brewer](ColorBrewer.png)](http://www.colorbrewer2.org)

### Choosing the right colormap for visualization
[![Color Advice](https://www.kennethmoreland.com/color-advice/smooth-cool-warm/smooth-cool-warm-3d.png)](https://www.kennethmoreland.com/color-advice/)
