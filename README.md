# IdPDE GitHub Manual

The IdPDE GitHub organisation provides a central place to store, maintain, and document research projects. 

GitHub is used to:

* preserve project knowledge after students graduate
* facilitate collaboration between researchers
* provide version history of documents and software
* share software and documentation where appropriate
* improve reproducibility of research

## Terminology

| Term  | Meaning |
| --- | --- |
| Organisation | IdPDE |
| Repository | One research project |
| Branch | Parallel version of a project |
| Commit | Save changes |
| Push | Upload saved changes |
| Pull | Download changes |
| Clone | Make local copy of repository |
| README | Project homepage |

## Choosing the appropriate workflow
There are three different workflows with increasing level of complexity and options.

| If you want to...                              | Recommended workflow |
| ---------------------------------------------- | -------------------- |
| Upload documents or update project information | [Level 1 - GitHub web interface](manual/github_web_browser.md) |
| Work on project files regularly                | Level 2 - GitHub Desktop       |
| Develop software or work on Linux/ROS systems  | [Level 3 - Git Command Line](manual/github_command_line.md) |


### Level 1 – GitHub web interface
No software installation is required.

Typical tasks:

* Create a new repository from the IdPDE project template.
* Upload documents.
* Update the project README.
* Add figures.
* Download project files.
* Review documentation.

No Git knowledge is required.

Full instructions can be found [here](manual/github_web_browser.md)

### Level 2 – Using GitHub Desktop (TBA)
GitHub Desktop synchronises a local folder on your computer with the repository on GitHub.

Typical workflow

1. Clone the repository to your computer.
2. Work on your files using your normal software.
3. Open GitHub Desktop.
4. Review the changed files.
5. Enter a short description of your changes.
6. Commit.
7. Push the changes to GitHub.

No command-line knowledge is required.

### Level 3 – Using Git from the command line
This workflow offers the greatest flexibility and is particularly suitable for Linux-based development environments such as ROS.

Typical commands include:

* Clone a repository
* Pull updates
* Commit changes
* Push changes
* Create branches
* Merge branches

Full instructions can be found [here](manual/github_command_line.md)

## Repository structure

Each project repository should contain enough information for another researcher to understand the project.
You can use the repository template found [here](https://github.com/IdPDE/repository-template) and click "Use this template".

A typical repository contains:

* README
* Documentation
* Source code (if applicable)
* Example data
* Results
* Figures

## Documentation

Every repository should answer the following questions:

* What is this project?
* What is the goal?
* How can someone reproduce or continue the work?

A repository should remain understandable after the original student or researcher has left the project.
You can use the repository template to start documenting a project.
