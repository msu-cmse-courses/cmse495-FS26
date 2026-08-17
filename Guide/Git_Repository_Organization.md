---
layout: guide
title: "Code must be Safe, Portable, Reproducible, Robust and Literate"
order: 33
mode: "guide"
---
# Code must be Safe, Portable, Reproducible, Robust and Literate

All members of your team must review the [Guidelines for Project Code Repositories](https://colbrydi.github.io/Research_guidelines/Rules_for_Repos.html) and you will be graded on how well your team follows these guildlines.  

# Git Repository Organization

<img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png"
       alt="Git Logo"
       style="max-width:100%; height:auto; flex:1 1 300px;">
       
Your git repository should be easy for teammates, instructors, and future maintainers to understand.


# Understanding Git

It is assumed that you have been introduced to git in previous classes. We will be using it a lot in this class. Students that are uncomfortable with git may want to find and and use a git tutorial. It is the entire teams responsibility to help your fellow members learn and use git properly. A fun place to start is the following game which tries to teach you git:

- [Git Game](https://ohmygit.org/)


## Minimum Repository Structure

```
ProjectName/
  README.md
  .gitignore
  LICENSE
  src/
  docs/
  data/
  notebooks/
  tests/
  environment.yml or requirements.txt
  INSTALL.md
```

Adjust names for your project, but keep structure intentional and documented.

## Core Expectations

- README explains project purpose and navigation
- INSTALL instructions are clear and tested
- Demo code runs after installation
- Commit history reflects contributions from all team members
- File/folder names are consistent and professional

## Tooling and Collaboration

Use issues and pull requests for substantial changes. Keep changes reviewable and describe why they were made.

## Privacy and Access

If your project has NDA/IP constraints, use an approved private repository configuration and ensure instructors have access.

# 2. Git Repository

Create a git repository and share it with your teammates and instructors.  This repository will be used for the remainder of the course to track all of your code developed for this project. By the end of the semester your repository needs to be well organized and easy to navigate.  Use best practices established by other communities. For example, here is a structure you may want to follow:

    ProjectName/
        .gitignore
        docs/
             package_name/
                  module1.html
                  module2.html
             images/
                  image1.jpg
        environments.yml
        Examples/
              datafile1.csv
              datafile2.tiff
              datafile3.xls
        LICENSE.txt
        makefile
        package_name/
              __init__.py
              module1.py
              module2.py
              test/
                  __init__.py
                  test_module1.py
                  test_module2.py
        README.md
        setup.py

Projects structure will vary. The important part is that repositories are well documented so that it is easy to navigate.  

Again, the ```README``` file is  extremely important and should be the first "touch point" in your files in your repository. Write the readme in a way that assumes that people reading it know nothing about the project. This means you include a brief description of the class and then guild people to the other parts of the project.  All files should be documented and clearly labeled.  There should be no confusion about what a file is and why it is in the folder.  

### Examples

Here is an example projects you can download from a different course with a similar structure. Note these may have had slightly different expectation and assignment goals relative to your project but are still good representation of the types of projects that would be acceptable for this course.  Projects shared with permission by former students:

- [S25 TwoSix](https://github.com/wangzey5/TwoSix_Spring25)
- [S25 MSU Rev](https://gitlab.msu.edu/vattiku1/hfh-revenue-cycle-predictive-analytics)
- [S25 MSU Justice for Otsego](https://github.com/uzairname/OtsegoStoryProject)
- [S24 Intramotev Autonomous Trains Object Detection](https://github.com/aryandhr/Autonomous-Trains-Object-Detection)
- [S24 TwoSix Fuzzy LLMs](https://github.com/riggsash/TwoSix_LLM)
- [F19 Neutrino Winds - By Brian Nevins](https://github.com/bnevs88/neutrino-winds)
- [F19 Enhanced sampling Methods - By Nicole Roussey](https://gitlab.msu.edu/roussey1/nmr_fs19_cmse802.git)
- [F19 Visualization of the Transport of Small Molecules on Peptides - By Xie Yan](https://gitlab.msu.edu/xieyan/yanxiecmse802.git)

Even more projects (may require logging into MSU GitLab to access:
- [F19 Lattice QCD Data Analysis - By Matthew Zeilbeck](https://gitlab.msu.edu/zeilbec1/zeilbec1_cmse802)
- [F19 A Tool for Applying Postseismic Corrections to Geodetic Data - By Connor Drooff](https://gitlab.msu.edu/drooffco/cmse-802-drooff.git)
- [F19 OMR Extracter - By Babak Safae](https://gitlab.msu.edu/safaeiba/ocr-omr-reader)




### GitHub vs GitLab vs Other

If your code is under and IP agreement then you are required to use the [MSU Gitlab (https://gitlab.msu.edu)](https://gitlab.msu.edu) server for hosting your private git repository.  This requirement can be waived if you have written permission from the IP owner asking that you use another git service (as long as your instructor has access).  

If your code is not under an IP agreement then your instructors are flexible as to which online git source you use.  Here are things to consider:

- If you want a private repository (i.e. only people you specify can see it) then we suggest the [MSU Gitlab](http://gitlab.msu.edu) server (it is free and secure).
- If you want your code to be public and open then we recommend using [Github](http://github.org) as it is the most popular online git server.
- You can always use more than one service and/or switch later in the semester.  Generally it is easier to start with a secure site such as [MSU Gitlab](http://gitlab.msu.edu) and get less secure than it is to start open and try to make it more secure.

Talk to your instructors if you have any problems.


### Basic git INSTRUCTIONS

For this milestone we only need to set up the basic structure with the following. To start, please keep the files simple and do not include files that do not add something to the project (see "what not to include" below):

    ProjectName/
        .gitignore
        LICENSE.md
        README.md
            
Here is a description of each of these:

* ```ProjectName``` - The top level folder is the short name of your team. Give your project a short and memorable name. An ideal name should be descriptive and have meaning to people who may be interested in using your software. A poor name only has meaning to your team. For example, **_DO NOT USE CMSE495_** in the the name.  Instead try to pick a name that relates to your project or what you think your project will do.  Although we can change the name later it is much easier if we pick a good name to start. 
    * ```README.md``` - This is a description of your git repository written in Markdown. 
    * ```.gitignore``` - There are a lot of files that are inappropriate to include in a git repository (more information below) the "Git Ignore" file helps by telling Git that you never want to use these files.  There are plenty of examples for good ```.gitignore``` files for Python projects on the Internet.  Try to include one that makes sense (you can update it as the semester goes on).
    * ```LICENSE.md``` - Use this file to describe your license (See section below).  
    
**_HINT_**:  Many of you may find this [git template](https://github.com/colbrydi/CMSE802_Project_Template.git) helpful.
        
If you need help figuring out how to set up your git repository there are a ton of tutorials online. For example here is a good one:

* [git game](https://ohmygit.org/)
* [GitBrancing tutorial](https://learngitbranching.js.org/)
* [Dirk's Full Getting to Know Git Tutorial](https://msu-cmse-courses.github.io/cmse802-f20-student/0000-Getting-to-know-git.html)

If you continue to need help go see your instructors. 





<iframe
    width="100%"
    height="300"
    src="https://www.youtube.com/embed/IAAv4DjYYUA?cc_load_policy=True"
    frameborder="0"
    allowfullscreen

></iframe>




The following video are instructions specifically for how to use the MSU Gitlab.  We will be using the MSU gitlab for all projects because it allows us to best maintain file permissions.  If you have a completely opensource project with no NDA or IP agreement you are also allowed to post on Github or other public spaces:





<iframe
    width="100%"
    height="300"
    src="https://www.youtube.com/embed/6_cegMFG0Pw?cc_load_policy=True"
    frameborder="0"
    allowfullscreen

></iframe>




Some of you may get some sort of "Authentication" error when trying to use git on a windows machine (especially if you have your computer already set up to use github). If that is the case, the following video may help you set up an SSH key on your windows machine.  

- [Direct Link to Windows SSH key generation video](https://youtu.be/b6umB61CV5s)





<iframe
    width="100%"
    height="300"
    src="https://www.youtube.com/embed/b6umB61CV5s?cc_load_policy=True"
    frameborder="0"
    allowfullscreen

></iframe>




As you update and change the files in your repository you will need to push those changes to gitlab.  The following instructions walk you though this process:





<iframe
    width="100%"
    height="300"
    src="https://www.youtube.com/embed/GTM-h5xX2Lk?cc_load_policy=True"
    frameborder="0"
    allowfullscreen

></iframe>




----

### What not to include (building a .gitignore file)

First thing we want to remember is that not everything should go into a git repository.  i.e. we do not want to bloat our repository with unwanted files.  The git repository works best with Text files that represent "source" code and not compiled or generated code. Here are some basic guidelines of what not to include:


* ```Secure Data``` - ***DO NOT*** include secure data under an NDA in your repository. This should only go in your teams folder.  
* ```.ipynb_checkpoint``` - These folders are generated when you run jupyter notebooks.  They are "temporary" compiled folders that will change each time you run your notebook and should not be included in your repository. 
* ```__pychache__``` - Similar to .ipynb_checkpoint folders these folders are often generated when running python scripts and should not be included in your repository. 
* **_Other "Temporary" files_** - Temporary files are generated by all types of software and often start with a special characters such as the dot (.) or the tilde (~).  For example many text editors generate temporary files to save a document in case of a program crash.  Do not include temporary files in your repository. 
* **_Compiled Code_** - Programs such as C and FORTRAN must compile their code to an executable in order to run on your computer. These compiled codes are not editable and should be left out of your repository.  Instead it is better to include instructions for compiling the source code as part of your repository.  
* **_Program Output_** - Do not include any program output in your repository (unless for very specific reasons such as documentation, testing, or figures in your final report).  Assume that any output that can be generated by the source code should not be included with the source code (it is redundant). 

A good rule of thumb is that if you did not generate the file and/or do not know what it is you probably do NOT want to include it in your repository. 

**_WARNING_** do not blindly add all files to your repository with the * (star) syntax.  This is bad practice. For example do NOT do the following:

~~```git add *```~~

### Other files to avoid

In addition to the above files it is good to avoid any type of "Binary" file (with a few exceptions).  As stated early, git works best with text files so it can easily track changes. Some example binary files to avoid include:

- **_Large Data files_**  Although it is good to include a few non-secret example inputs to your software, avoid using entire datasets.  It is best to store large data files someplace else (ex. Teams folder).
- **_Non-Text formats_** such as Word, Excel or PowerPoint documents should be avoided.  These tend to change each time they are opened even if the core text does not change. it is better to use an alternative text example. 


**_Note:_** one exception to the above rules are image files (ex jpg or png) that are used to help markdown or in the documentation.  It is typically okay to include these since they tend to get included only once and do not change much as the project evolves. 


### .gitignore file

The ```.gitignore``` (read "dot git ignore") file is used to help keep unwanted files out of your project.  Each line ```.gitignore``` file are filenames you want git to ignore.  For example, based on what we said above, a  good place to start on your ```.gitignore``` file would be the following two lines:
```
.ipynbcheckpoint
__pychache__
```

What should go into a .gitignore depends a lot on the type of project.  However, you don't need to invent these from scratch. For example, you could just copy the .gitignore file from the course repository or find one on the internet.





<iframe
    width="100%"
    height="360"
    src="https://www.youtube.com/embed/kzI-mPSY8y4?cc_load_policy=True"
    frameborder="0"
    allowfullscreen

></iframe>




----


### README.md file

Make sure your git repository has a ```README.md``` file.  This file is very important as it will be the first place everyone will look when they first get your repository.  Write this as if someone in the future stumbles across your folder.  Include a brief description of the class, the community partner, the project and the goals of this repository.  Link to any installation instructions or getting started instructions.  It is important that this file guides readers to the rest of the repository. A great resource for writing a well thought out README file can be found here:

<https://readme.so/editor>



----

### Jupyter notebook files in git repositories

Turns out that Jupyter notebook files and git repositories work very poorly together.  Jupyter notebook files are a unique combination of source and program generated information.  So, every time you run a jupyter file it can add output cells which make git think you you changed something important. In many cases it is just a few numbers or some output text.  When you run the ```git status``` command it always looks like jupyter notebook files have changed even when they have not changed. 

A good rule of thumb is to clear all of the output files before committing any changes to jupyter notebook files.  

- Open the jupyter notebook file
- Select "Reset Kernel and clear output" from the menu
- Save the notebook file.
- Do your "git add" and "git commit" commands

The following video goes though why we have to treat jupyter notebooks this way:

[Direct Link](https://www.youtube.com/embed/79hW_TzLos8)





<iframe
    width="100%"
    height="300"
    src="https://www.youtube.com/embed/79hW_TzLos8?cc_load_policy=True"
    frameborder="0"
    allowfullscreen

></iframe>




---

### Licensing file

As authors of software it is important to let people know how they can use our software. 

***If your project has an IP agreement you should include an unsigned copy of the agreement and include a LICENSE file similar to the following.*** 

```
License Agreement

This software is the intellectual property of [COMMUNITY PARTNER NAME] and was developed by the [TEAM NAME] Capstone team, consisting of [Name1], [Name2], [Name3]...

The use of this software is governed by the terms and conditions outlined in the attached Intellectual Property Agreement (IP Agreement) identified as [FILENAME].

By using this software, you agree to comply with the terms of the IP Agreement.
```


***If you do not have an IP agreement that covers the License, the following article is a great resource for learning the types of terminology and logic used when talking about software License.***  

* <https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002598>

* <https://creativecommons.org/licenses/>


![Creative commons license](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)

Include a ```./LICENSE``` test file in your top directory. Select which license to use using the following website:

* [https://choosealicense.com/](https://choosealicense.com/)

Copy and paste your chosen license file into a file named ```./LICENSE```

The following articles are a great resource for learning the types of terminology and logic used when talking about software License.  

* <https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002598>
* <https://choosealicense.com/>
* <https://creativecommons.org/licenses/>

**_Make sure you talk to your instructors to know what type of license is appropriate for your project given.  What license you use may also depend on the IP agreement made with you and the community partner._**

Include a ```./LICENSE.txt``` test file in your top directory.


# 3. Working with files professionally

Anytime you are working with files you need to pay attention to what you are doing.  Pay attention to whom you will be sharing files and keep things clean and professional.  Points will be taken off for unprofessional files. 

Consider the following guidelines.

---

### Use Filenames that make sense

 Make sure the contents of the files are clear.  If something is associated with a specific date then would like to use the following format:

    YYYYMMDD-TEAM-Contents.ext
    
- ```YYYY``` - Year file (ex, 2023)
- ```MM``` - Two diget Month (ex. 01 for January)
- ```DD``` - Two diget Day (ex. 09 )
- ```TEAM``` - Short team name (if not obvious in context.
- ```Contents``` - Content of the file.

---

### DO NOT use spaces in file names

I said this above and I will say it again. 

When you name all of the files and folders inside of a repository, it is important that your names **_DO NOT include spaces_**.  Although all modern computer's have ways to accept names with spaces do not use them.  Instead use underscores (\_) or ```CamelCase``` (No spaces and capital letters at the beginning of each word in the name).  Avoiding spaces in your names will **_Always_** save time in the long run.  

----

### Always Use Relative Paths

In your code there are two basic ways to determine the location of a folder inside your computer; Relative Paths and Absolute Paths.  A relative path is a path starting from your current directory and an absolute path is is a path starting from your computer's "root" directory.  

- Relative paths typically start with a single dot (.), representing the current directory, or two double dots (..) representing the current directories parent folder.
- Absolute paths typically start at the global root directory (/) on a Linux or Mac machine or with a drive label (ex C:) on a windows machine.  

**_ALWAYS_** use relative paths in your git repository.  This ensures that others will be able to use your software if they download it onto their computer.  For example:

    Good: ./data/  or ../data/ is a relative path to a child directory or sibling directory called data. 
    
    mBad (not acceptable): C:/research/data or /mnt/home/data are absolute paths to a data directory
 
 

<!-- TOC_START -->
<div class="page-toc">
<h2>On this page</h2>

<details>
<summary>Code must be Safe, Portable, Reproducible, Robust and Literate</summary>
<ul>

</ul>
</details>

<details>
<summary>Git Repository Organization</summary>
<ul>

</ul>
</details>

<details>
<summary>Understanding Git</summary>
<ul>

<li><a href="#minimum-repository-structure">Minimum Repository Structure</a></li>
<li><a href="#core-expectations">Core Expectations</a></li>
<li><a href="#tooling-and-collaboration">Tooling and Collaboration</a></li>
<li><a href="#privacy-and-access">Privacy and Access</a></li>
</ul>
</details>

<details>
<summary>2. Git Repository</summary>
<ul>

<ul>
<li><a href="#examples">Examples</a></li>
<li><a href="#github-vs-gitlab-vs-other">GitHub vs GitLab vs Other</a></li>
<li><a href="#basic-git-instructions">Basic git INSTRUCTIONS</a></li>
<li><a href="#what-not-to-include-building-a-gitignore-file">What not to include (building a .gitignore file)</a></li>
<li><a href="#other-files-to-avoid">Other files to avoid</a></li>
<li><a href="#gitignore-file">.gitignore file</a></li>
<li><a href="#readmemd-file">README.md file</a></li>
<li><a href="#jupyter-notebook-files-in-git-repositories">Jupyter notebook files in git repositories</a></li>
<li><a href="#licensing-file">Licensing file</a></li>
</ul>
</ul>
</details>

<details>
<summary>3. Working with files professionally</summary>
<ul>

<ul>
<li><a href="#use-filenames-that-make-sense">Use Filenames that make sense</a></li>
<li><a href="#do-not-use-spaces-in-file-names">DO NOT use spaces in file names</a></li>
<li><a href="#always-use-relative-paths">Always Use Relative Paths</a></li>
</ul>
</ul>
</details>
</div>
<!-- TOC_END -->
