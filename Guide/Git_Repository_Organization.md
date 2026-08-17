---
layout: guide
title: "Git Repository Expectations"
order: 33
mode: "guide"
---
# Git Repository Expectations

<img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png"
       alt="Git Logo"
       style="max-width:100%; height:auto; flex:1 1 300px;">
       
All project teams must maintain a shared Git repository throughout the semester. The repository serves as the primary location for project code, documentation, and collaboration.

Your repository should be organized, well documented, and easy for teammates, instructors, and future maintainers to navigate. Teams will be evaluated not only on the quality of their final product, but also on the professionalism of their repository. All team members should review the Guidelines for Project Code Repositories:

[Rules for Git Repositories](https://colbrydi.github.io/Research_guidelines/Rules_for_Repos.html)

Git is an essential tool for this course. Students who are not yet comfortable with Git should invest time in learning the basics early in the semester. Learning Git is a team responsibility, and experienced team members should help others develop good version control habits.

Recommended tutorials and resources:

- [Git Game](https://ohmygit.org/)
- [Learn Git Branching](https://learngitbranching.js.org/)

If you continue to struggle with Git, please talk with your instructors as early as possible.

## Repository Structure

Project repositories will vary, but most should contain some version of the following structure:

```
ProjectName/
  README.md
  .gitignore
  LICENSE
  src/
  docs/
  example_data/
  tests/
  environment.yml or requirements.txt
  INSTALL.md
```

Adjust the structure to fit your project, but keep the organization intentional and documented.


## Required Practices

Your repository should:

- Include a README that explains the project and guides readers through the repository.
- Be organized, well documented, and easy for teammates, instructors, and future maintainers to navigate.
- Use meaningful file names, folder names, and commit messages.
- NOT include spaces in folder and filenames.
- Contain installation, setup, and reproduction instructions when appropriate.
- Document software dependencies, workflows, and assumptions so others can reproduce your work.
- Demonstrate contributions from all team members.
- Ensure all team members understand and actively participate in the repository workflow.
- Use issues and other Git collaboration tools to document work, decisions, and project progress.
- Follow good software practices, including the use of relative paths, documentation, and an appropriate .gitignore file.
- Exclude temporary files, generated output, confidential data, passwords, API keys, and other sensitive information.

The README is often the first thing someone sees when they visit your repository. Write it for an audience that knows nothing about your project. Explain the purpose of the repository and guide readers to the appropriate documentation, code, data, and resources.

Your repository should be organized as if another team will inherit the project after the semester ends. A new developer should be able to understand the purpose of the project, reproduce key results, and continue development with minimal assistance.

## Collaboration

Git should be used throughout the semester rather than only near project deadlines. Regular commits help document progress, reduce merge conflicts, and make it easier to recover from mistakes.

For substantial changes, consider using issues and pull requests to document decisions, distribute work, and review contributions. Use these tools professionally, as they become part of the project's permanent record and provide a useful history of how the project evolved.

## Repository Access

If your project involves confidential data, intellectual property agreements, or NDA restrictions, use [MSU Gitlab](http://gitlab.msu.edu) private repository and ensure all instructors have access.

Projects without such restrictions may use GitHub, public GitLab, or another approved hosting service.

## Files That Should Not Be Tracked

Do not commit:

- Confidential or restricted data
- Temporary files
- Generated output files
- Compiled binaries
- Jupyter checkpoint files
- Python cache files
- Large datasets that can be stored elsewhere

Your .gitignore file should be configured appropriately for your project.

## Jupyter Notebooks

Jupyter notebooks often contain output cells that change every time a notebook is executed. Before committing notebooks, clear unnecessary output and verify that only meaningful changes are included in the commit.

## Example Repositories

The following repositories demonstrate the level of organization and documentation expected in CMSE project work. These examples come from previous student teams and are shared with permission:

- [S25 TwoSix](https://github.com/wangzey5/TwoSix_Spring25)
- [S25 MSU Rev](https://gitlab.msu.edu/vattiku1/hfh-revenue-cycle-predictive-analytics)
- [S25 Justice for Otsego](https://github.com/uzairname/OtsegoStoryProject)
- [S24 Intramotev Autonomous Trains Object Detection](https://github.com/aryandhr/Autonomous-Trains-Object-Detection)
- [S24 TwoSix Fuzzy LLMs](https://github.com/riggsash/TwoSix_LLM)
- [F19 Neutrino Winds](https://github.com/bnevs88/neutrino-winds)
- [F19 Enhanced Sampling Methods](https://gitlab.msu.edu/roussey1/nmr_fs19_cmse802.git)
- [F19 Visualization of the Transport of Small Molecules on Peptides](https://gitlab.msu.edu/xieyan/yanxiecmse802.git)

There is no single correct repository layout. The goal is to create a repository that is professional, well documented, easy to navigate, and maintainable by others long after the semester ends.

<!-- TOC_START -->
<div class="page-toc">
<h2>On this page</h2>

<details>
<summary>Git Repository Expectations</summary>
<ul>

<li><a href="#repository-structure">Repository Structure</a></li>
<li><a href="#required-practices">Required Practices</a></li>
<li><a href="#collaboration">Collaboration</a></li>
<li><a href="#repository-access">Repository Access</a></li>
<li><a href="#files-that-should-not-be-tracked">Files That Should Not Be Tracked</a></li>
<li><a href="#jupyter-notebooks">Jupyter Notebooks</a></li>
<li><a href="#example-repositories">Example Repositories</a></li>
</ul>
</details>
</div>
<!-- TOC_END -->
