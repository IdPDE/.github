# Level 3 – Using Git(Hub) from the command line
This workflow is intended for advanced users developing software, particularly on Linux-based systems such as ROS.

## Before we begin..
* Install Git
* Configure Git
  *  Username
  *   Email address
* Verify that SSH keys or authentication are correctly configured for GitHub.

## Cloning a repository (local copy)

* Create a workspace
```bash
mkdir -p ~/<workspace-name>
```
* Move into the workspace
```bash
cd ~/<workspace-name>
```

* Clone the repository once:

```bash
git clone <repository-url>
```

* Move into the project:

```bash
cd repository-name
```

## Standard workflow

The standard workflow consists of four steps.

### Step 1 – Pull

Before making changes, ensure you're on the latest version:

```bash
git pull
```

### Step 2 – Modify files

Edit files normally.

### Step 3 – Commit

View changed files:

```bash
git status
```

Stage files:

```bash
git add .
```

Commit:

```bash
git commit -m "Describe your changes"
```

Choose commit messages that explain the purpose of the change rather than simply stating what was edited.

### Step 4 – Push

Upload your work:
```bash
git push
```
The repository on GitHub is now updated.

## Viewing project history

To inspect previous work:
```bash
git log
```

This shows:

* Author
* Date
* Commit message

More information on general Git commands can be found [here](https://github.com/devaaravmishra/git-commands).

## Working with branches

Branches allow experimental work without affecting the main project.
You can create a new branch from existing work as follows:
```bash
git checkout -b <new-branch-name>
```

Typical workflow:

Create branch &rarr; Develop feature &rarr; Commit changes &rarr; Push branch &rarr; Merge into main

Branches are recommended for larger software developments but are generally unnecessary for documentation updates.
More information on branching can be found [here](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging).


