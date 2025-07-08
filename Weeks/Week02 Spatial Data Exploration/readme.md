---
marp: true
theme: uncover
headingDivider: 3
footer: PA405 | Intro to GIS and Spatial Data Science ![width:30px](../images/globe.png)
paginate: true

---

<style>
kesmall {font-size:0.6em}
medium {font-size:0.9em}
large {font-size:2em}
xlarge {font-size:4em}
gray {padding:20px;background-color:whitesmoke;font-weight:800}
plum {padding:20px;background-color:plum;line-height:3}
xl { font-size:2.5em;font-weight:100;line-height:1}
h1,h2,h3,h4,h5{font-family:serif}
section {font-size:2em;font-weight:300;}
</style>

# Week 2

<xl>

Spatial Data Exploration

</xl>

[Course zoom link for Summer Quarter 2025](https://ucla.zoom.us/j/95264672205?pwd=tcbEUfAy5GXNpXtf01UTrO1dnk2IQj.1)

July 8, 2025

##
<xl>

*Note that this course will be recorded🎥

</xl>

##

<xl>
Resources for ICE Raids </br>(Day 32)
</xl>

##

<xl> Volunteer, recovery, and relief resources
<xl>

* [Comprehensive Know Your Rights Guide Against ICE Raids](https://cd14.lacity.gov/community-resources/know-your-rights#:~:text=Southern%20California%20Rapid%20Response%20Network,%3A%20(213)%20201%2D3773).  
* [UCLA Labor Raids Resource List](https://labor.ucla.edu/immigration-raids-in-los-angeles-solidarity-statement-and-resource-list/)

* [How to get involved beyond protesting](https://lapublicpress.org/2025/06/la-protest-resources-ice/)

* [Boyle Heights Beat donate, volunteer, support](https://boyleheightsbeat.com/support-donate-volunteer-los-angeles-immigration-raid-protests/)

* [CHIRLA](https://www.chirla.org/)



##

<xl> GIS resources
<xl>

* [ICEwatch Tactics Map](https://www.immigrantdefenseproject.org/icewatch/)

* [People over Papers Map](https://boyleheightsbeat.com/ice-raid-tracking-app-los-angeles/)


### Project formation for midterm and final projects
<span style="font-size=20px">

* Open and review the [midterm and final project guidelines](https://github.com/cgiamarino9/PubAff405_S25/tree/main/Midterm%20and%20Finals#midterms-and-finals). </span>

* The form is not graded, but it will help you with your midterm proposal due before Week 3. You are welcome to submit the [project proposal assignment](https://my.uclaextension.edu/courses/55582/assignments/987734?module_item_id=3496629) when your group is ready. It is due July 14th at 11:59 pm. 
</span>


## Hands on Lab
First, grab the course material, and "pull" it into your JupyterHub space:

* [Git related](https://github.com/cgiamarino9/PubAff405_S25/blob/main/Git%20related/01%20-%20Getting%20started%20every%20week.md) 

<small>Note that you have to do this at the start of every lecture to get the latest material.
</small>


# Assignments (due 11:59 pm, Monday, July 14th the day before class)


## Individual assignment: Data Exploration

### Create a token

In order to pull and push content to GitHub, you must first create a token, which will serve as your password. Refer to this tutorial to create your token:

* [How to create a token](https://github.com/cgiamarino9/PubAff405_S25/blob/main/Git%20related/Create%20a%20token.md)

### Clone your repo

This is your first code assignment submission. Before you begin, create a clone of your repo in JupyterHub.

* [How to clone your repo into JupyterHub](https://github.com/cgiamarino9/PubAff405_S25/blob/main/Git%20related/Clone%20repo%20to%20hub.md)

### Submission guidelines:

- Find and download a dataset of your choice. This can be a shapefile, csv file, or json file. For many of you, you may have already done this as part of your week 1 assignments.
- Launch JupyterHub, go to your `pa405` repo folder, and create a `week02` folder.
- Load the dataset to the `pa405/week02` folder.

### 
Download git just in case 

* [Git for Windows and Mac installation](https://github.com/git-guides/install-git)
* [Tutorial for cloning, pushing, and pulling on JupyterLab 'ReviewNB'](https://blog.reviewnb.com/jupyterlab-git-extension/)
* [Clone, push, pull from JupyterLab to GitHub](https://youtu.be/Rbg2YMWoGGo?si=LJAYsXpcHHoHC4Sa).
**Please note**: it is recommended that you only upload your data and start your notebooks for individual assignments on JupyterLab and push them to GitHub. GitHub is where you publish your final JupyterLab notebooks. If you start working on GitHub and forget when you did upload to GitHub, you will start running into pull and push errors. 
* [Creating personal (classic) access token on GitHub](https://medium.com/@mbohlip/how-to-generate-a-classic-personal-access-token-in-github-04985b5432c7)

### 
Create a new python notebook 
**Do not** work on a copy of the lab notebook

<kbd><img src="images/notebook.png" width=75%></kbd>

###

Right click on the `Untitled.ipynb` tab and rename the notebook to `week2assignment.ipynb` or `assignment2.ipynb`. Just be consistent throughout the quarter. 

<kbd><img src="images/rename.png" height=75% ></kbd>

###

Add an introductory markdown cell with a title (header) and paragraph that describes what you are doing.

###

Import the data, and conduct data exploration, making sure to document your steps and your preliminary findings. At minimum, run the following commands:

* `.shape`
* `.info`
* `.head()`
* `.plot()`
* `.value_counts()`
* run a query on the data that filters it in some way

###

For each code cell, add a markdown cell that explains what you are doing.

Add markdown cells that describe the output of each operation.

Save your notebook.

### Commit your changes to your GitHub class repo.

Commit your changes to your GitHub repo by following these instructions:

* [How to commit and push to your repo](https://github.com/cgiamarino9/PubAff405_S25/blob/main/Git%20related/Commit%20and%20push.md)

### Submit your assignment 

The last step is to submit your assignment to the class repo discussion section [here](https://my.uclaextension.edu/courses/55582/assignments/987733).

# Project Assignment #1
## <xl>Project Proposal</xl>
<hr>

<left>

The course will largely be guided by your final project, which will be conducted individually. Consider that your final project will be a representation of what you learn in this course, and how you apply it on a project level. Consider also that your final project can serve to showcase your data science and mapping skills, which may become a valuable asset for your career moving forward.


### Step 1: Plan
<hr>

<left>
Discuss and identify a research question, identify and collect data, articulate how you intend to use and analyze it, and begin to speculate how the data can answer your research inquiry. Understand that this may change later, especially as we learn more about what we can do with our methods, and also, as you find the data sources that can or cannot support your research.

### Step 2: Data
<hr>
<left>
Next, identify and download at least two datasets that you believe can guide your research. Make sure that at least one of them has a spatial component. For example, if one of your datasets comes from the census, identify which survey you will use (e.g. Decennial or American Community Survey), and which variables you will select. Note that we will be covering census data in detail in Week 3. Your second dataset should come from a separate source. For example, you may want to do a crime analysis and obtain data from the LA Data Portal.

### Step 3: Create a project repo. 

1. Create a new repository for your project
3. Go to Settings, Manage Access, and add your partner as a collaborator
1. Create a Project Assignments folder (hint: click on Add File, Create new File, and enter "Project Assignments/readme.md" in the text box). I recommend that you do this in Jupyter Lab.
4. Create a markdown file for your project proposal

### Step 4: Write your proposal
<hr>

<medium>

Your project proposal should include the following:
*   An introduction of your research question
*   An explanation of why it is important to you, why it matters to others, and what is at stake
*   A description of the spatial scope (e.g. Boyle Heights or Hong Kong), and why space and/or time matters for your project
*   A preliminary but definitive description of data sources (at least two) that you will use
    * Include datasource with links
*   A scope that explains the intended analysis and resulting visualizations for your project
*   A concluding paragraph of what insights you expect to gain from your research

### Step 5: Submit
Submit your assignment [here](https://my.uclaextension.edu/courses/55582/assignments/987734)