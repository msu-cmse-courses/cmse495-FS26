# Reproducibility

![Example project figure](https://www.researchgate.net/publication/374654731/figure/fig4/AS:11431281197917308@1697128184444/Example-of-tea-pest-data-visualization.png)

- Image from <http://dx.doi.org/10.15439/2023F6100>

The goal of this assignment it to continue to review the installation instructions and ensure the reproducibility of the project by making individual instructions that can be used to generate project figures.   All figures you generate as part of your project should follow these guidelines in your final deliverables.  This milestone is for you to complete at least one figure and demonstrate your understanding of what is expected in your final project.

----

# 1. Deliverables

Generate an instruction file (typically a Jupyter notebook file is ideal because it can include code, however a markdown file may also be appropriate) with complete instructions that describe how you created each of your figures for your project.  Basically any figure you generate should have complete instructions about how that figure was generated.  

Some projects may only use one file to generate all figures while other projects may use more than one depending on the workflows.  It is important that **ALL** of the figures in your final report have instructions on how those specific figures were generated. 

# 2. What to include

Typical instructions should include the following:

- Description of the figure(s) the instructions for and where the figure is used (In your presentation, in your reports, etc.)
- Link to instructions to install the raw data, software and dependencies (ex. your ```INSTALL.md``` file).
- Code to generate the required data used in the figure and instructions for any munging or analysis.
- Links to intermediate data that takes a while to generate.
- Code to generate the figure or visualizations.
- Code to add formatting such as axes labels, titles, etc.
- Procedure/code to export the figure.

As much as possible try to automate the instructions.  The best instructions will just allow the reviewer to run the notebook and produce the figure.  However, that may not be possible. Instead you need to include any manual steps.

If a step requires a lot of time, it is expected that intermediate results are stored so that the instructor could complete the time consuming step or skip over it.  If the data is still under the NDA please put the intermediate results in the Teams directory or contact the instructor before this assignment is due to agree on a work around.


---
# Submission

Although you will need instructions for all of your figures the goal of this project is to commit at least one figure instruction file to your project git repository on or before the due date. Make sure it is clear where the file is located (i.e. update your ```README.md``` file). Your instructor will download your repository and check your instructions and try to reproduce your results. 

# Evaluation and Rubric

Instructors will follow your instructions and try to reproduce your results. Points will be taken off for any missing or confusing steps.  

The following is a basic rubric that will be used to evaluate your submission.  Notice the similarity of this rubric from the Install Instructions assignment. Make sure you have addressed all of your feedback or your team will continue to get the same points removed.:

* (20 points) Professional submission of the files including proper use of the following:
    - file permissions so that instructors can access necessary files. 
    - filename and file structure. Example, no spaces in the filenames / folders, relative paths, etc.
    - .gitignore file in git repositories.
    - license file.
    - all students have contributed to the git repository and are using informative and professional commit messages. 
    - README file that includes purpose of projects and directions to install steps.
    - all files are well documented. (for example all jupyter notebooks files should use markdown, have titles and descriptions. Python and R files should all start with a minimum of a description of file and how it should be used). 
* (20 points) Proper Install Instructions with no confusing steps.
    - Instructions for installing software.
    - Instructions for testing the install.
    - Instructions for downloading example and/or example testing data.
    - Instructions for running the demo. 
* (10 points) Working demo code.
    - Demo code runs after install and seems to be working
* (50 points) Figure Reproducibility Instructions 
    - Instructors able to follow the instructions with no confusing or missing steps. 



----
Written by Dr. Dirk Colbry, Michigan State University
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
