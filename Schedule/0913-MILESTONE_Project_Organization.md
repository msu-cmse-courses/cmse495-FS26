---
layout: schedule
title: "Project Files - Organizing your Team and Project!"
order: 913
mode: "schedule"
---
# Project Files - Organizing your Team and Project!


<div style="display:flex; flex-wrap:wrap; justify-content:center; gap:1rem;">

  <img src="https://play-lh.googleusercontent.com/jKU64njy8urP89V1O63eJxMtvWjDGETPlHVIhDv9WZAYzsSxRWyWZkUlBJZj_HbkHA"
       alt="Microsoft Teams Logo"
       style="max-width:25%; height:auto; flex:1 1 30px;">

  <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png"
       alt="Git Logo"
       style="max-width:25%; height:auto; flex:1 1 30px;">

</div>

This project teams will organize both their Microsoft TEAMS Directory and github repository to prepare them for the semester. The key components of this assignment are to draft and organize the following: 

1. **_TEAM Charter_** Draft this "living" document that outlines your teams logistics. Please use [this link](../Guide/Team_Charter) to help build your charter and put the official copy in the top level of your TEAMS private folder. 
3. **_TEAMS Public Folder_** This is a sub-folder in the General channel and is used to share non sensitive files with your classmates. This folder is ONLY for temporary files and should not be the primary home for anything important. Move files from here to the Private folder if it is important. 
4.  **_TEAMS Private FOLDER_** Use this folder to store your primary team organizational documents. This includes the team charter, project data, meeting minutes, NDA/IP agreements, Weekly 3x3 Reports, report drafts, milestones, etc. Details about how to set up this folder can be found in [this link](../Guide/Team_Directory_Organization)
5. **_Git Repository_** Use this folder to track your teams software. We expect all teams to use good software management practices when dealing with code and a good version control system is key.  Details about how to set up your git repository can be found I [this link](../Guide/Git_Repository_Organization)

Organizing your files in a logical and clean manner is expected. Instructors should never have to question what they are referencing or have trouble finding documents. 

## Submission

Draft all documents and put them in the required locations.  

If you have an IP and NDA agreement have one (and only one) person from your team email the correctly signed documents to your instructors and your community partners. These MUST be professional emails.  You can ask an instructor to check it before hitting send.  




### Basic git INSTRUCTIONS

For this milestone we only need to set up the basic structure with the following. To start, please keep the files simple and do not include files that do not add something to the project (see "what not to include" below):

    ProjectName/
        .gitignore
        LICENSE.txt
        README.md
            
Here is a description of each of these:

* ```ProjectName``` - The top level folder is the short name of your team. Give your project a short and memorable name. An ideal name should be descriptive and have meaning to people who may be interested in using your software. A poor name only has meaning to your team. For example, **_DO NOT USE CMSE495_** in the the name.  Instead try to pick a name that relates to your project or what you think your project will do.  Although we can change the name later it is much easier if we pick a good name to start. 
    * ```README.md``` - This is a description of your git repository written in Markdown. 
    * ```.gitignore``` - There are a lot of files that are inappropriate to include in a git repository (more information below) the "Git Ignore" file helps by telling Git that you never want to use these files.  There are plenty of examples for good ```.gitignore``` files for Python projects on the Internet.  Try to include one that makes sense (you can update it as the semester goes on).
    * ```LICENSE``` - Use this file to describe your license (See [Git Repository Organization](https://msu-cmse-courses.github.io/cmse495-FS26/Guide/Git_Repository_Organization) in the team guild for more details).  
    
**_HINT_**:  Many of you may find this [git template](https://github.com/colbrydi/Research_Software_Project_Template) helpful.
        
If you need help figuring out how to set up your git repository there are a ton of tutorials online. For example here is a good one:

* [git game](https://ohmygit.org/)
* [GitBrancing tutorial](https://learngitbranching.js.org/)
* [Dirk's Full Getting to Know Git Tutorial](https://msu-cmse-courses.github.io/cmse802-FS26/Guide/31-Getting-to-know-git)

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



## Evaluation and Rubric

Project will be evaluated primary on a teams ability to read and following directions.  

Make sure your instructors and classmates have the correct permissions to access, clone your repositories and provide the full git command/instructions in your team charter.  

Your instructor will evaluate your assignment by reviewing the following:

- Review of team charter
- Checking pdfs of NDA and IP agreements (if required)
- Forking and cloning your repository using the link in your team charter
- Verify repository/files are hosted properly per NDA/IP agreements
- Reviewing of your git log
- Review of your repository README.md file
- Review of your repository LICENSE.md file
- Checking for reasonable .gitignore file

You will be graded on how well directions were followed and the professionalism of the submission.

Points will be taken off if your signed NDA/IP agreemnts are unprofessional.  

The following is an approximate rubric that will be used as a guild for evaluating this assignment. 

|                                                                |                            Meets  Expectations                        |                        Needs Improvement                    |              Incomplete          |   |
|----------------------------------------------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------:|:--------------------------------:|---|
| Repository README | Includes description of class and project (10 pts) | Present but lacking detail (5 pts) | Missing (0 pts)
| Repository gitignore| Present and includes approriate filetypes (5 pts) | Present but lacking important details (2 pts) | Missing (0 pts) 
| license | Present and correct (10 pts) | Incorrect license or doesn't meet NDA/IP agreement (5 pts) | Missing (0 pts)
|      Repository forking/cloning   |     Repo can be forked and cloned from link in team charter (10 pts)                          |    Repo premissions are incorrect (5 pts)                      |     Repo cannot be forked/clones (0 pts)    
| NDA/IP Agreements | Complete and correctly located (10 pts) | Not correctly located or nonprofessional (5 pts) | Missing (0 pts)
|      Team Charter Content                                      |     Charter includes all required sections and contact info (45 pts)  |     Charter missing at least one required element (35 pts)  |     No charter provided (0 pts)  |   |
|      Team Charter & Repository Formatting                      |     Overall repository well-organized (10 pts)                        |     Some repository organizational issues (5 pts)           |  Major missing or incomplete components (0 pts)   |   |


## Post-Evaluation

Review feedback from instructors and ensure that any requested changes are made. 

<!-- TOC_START -->
<div class="page-toc">
<h2>On this page</h2>

<details>
<summary>Project Files - Organizing your Team and Project!</summary>
<ul>

<li><a href="#submission">Submission</a></li>
<ul>
<li><a href="#basic-git-instructions">Basic git INSTRUCTIONS</a></li>
</ul>
<li><a href="#evaluation-and-rubric">Evaluation and Rubric</a></li>
<li><a href="#post-evaluation">Post-Evaluation</a></li>
</ul>
</details>
</div>
<!-- TOC_END -->
