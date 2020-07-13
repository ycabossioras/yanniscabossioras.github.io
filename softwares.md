<h1 align=center> Softwares Cheatsheet </h1>

Table of Contents

[TOC]

## Python

### Cheatsheets

* <a href="https://cheatsheets.quantecon.org/" target="_blank">Quant Econ cheatsheet for MATLAB, Python, Julia</a>



### Ressources

* <a href="http://www.xavierdupre.fr/app/ensae_teaching_cs/helpsphinx/notebooks/_gs1a_D_dataframe_matrice.html" target="_blank">ENSAE computer science class</a>
* <a href="http://eric.univ-lyon2.fr/~ricco/cours/index.html" target="_blank">Univ Lyon 2 class</a>
* <a href="https://medium.com/dunder-data/selecting-subsets-of-data-in-pandas-6fcd0170be9c" target="_blank">Selecting subsets of data in Pandas</a>
* <a href="https://informatique-python.readthedocs.io/fr/latest/Cours/science.html" target="_blank">NumPy, SciPi, MatPlotLib</a>
* <a href="https://lectures.quantecon.org/py/index.html" target="_blank">QuantEcon lectures</a>
* <a href="https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8" target="_blank">Logistic regression</a>



### Command Line

| Syntax                                           | Description                                                  |
| ------------------------------------------------ | ------------------------------------------------------------ |
| <kbd>python</kbd>                                | Launch Python in terminal                                    |
| <kbd>python *file.py*</kbd>                      | Run this command in the **shell** to run *file.py* in Python (first, set the current directory accordingly) |
| <kbd>exit()</kbd> / <kbd>CTRL</kbd>+<kbd>D</kbd> | Exit Python                                                  |
| <kbd>import *package*</kbd>                      | Import the package *package* in Python                       |
| <kbd>%lsmagic</kbd>                              | List all available magics                                    |
| <kbd>%...</kbd>                                  | Line magic                                                   |
| <kbd>%%...</kbd>                                 | Cell magic                                                   |
| <kbd>%...?</kbd>                                 | Open help for a particular magic                             |
| <kbd>%system *cmd*</kbd> / <kbd>!*cmd*</kbd>     | Run the UNIX command *cmd* (e.g. ls, pwd, etc.) as if in the terminal |
| <kbd>%%HTML</kbd>                                | Insert HTML code                                             |



### Spider



### Jupyter

| Syntax                            | Description                                                  |
| --------------------------------- | ------------------------------------------------------------ |
| <kbd>jupyter notebook</kbd>       | **Shell** command to open Jupyter (need to set the directory first because Jupyter opens the current directory) |
| <kbd>CTRL</kbd>+<kbd>C</kbd>      | **Shell** command to close Jupyter                           |
| <kbd>ESC</kbd>                    | Go from edit mode to command mode                            |
| <kbd>ENTER</kbd>                  | Enter edit mode                                              |
| <kbd>CTRL</kbd>+<kbd>ENTER</kbd>  | Execute the current cell (works in edit and command modes)   |
| <kbd>SHIFT</kbd>+<kbd>ENTER</kbd> | Execute the current cell and go to the next cell (works in edit and command modes) |
| <kbd>ALT</kbd>+<kbd>ENTER</kbd>   | New code cell (works in edit and command modes)              |

When in command mode:

| Syntax                            | Description                         |
| --------------------------------- | ----------------------------------- |
| <kbd>a</kbd>/<kbd>b</kbd>         | Insert cell above/below             |
| <kbd>d</kbd>,<kbd>d</kbd>         | Delete cell                         |
| <kbd>SHIFT</kbd>+<kbd>m</kbd>     | Merge cells                         |
| <kbd>y</kbd>                      | Convert current cell to a code cell |
| <kbd>m</kbd>                      | Convert current cell to a text cell |
| <kbd>r</kbd>                      | Convert current cell to a raw cell  |
| <kbd>z</kbd>                      | Undo action                         |
| <kbd>x</kbd>                      | Cut selected cell                   |
| <kbd>c</kbd>                      | Copy selected cell                  |
| <kbd>v</kbd>                      | Past cell                           |
| <kbd>SPACE</kbd>                  | Scroll down                         |
| <kbd>SHIFT</kbd>+<kbd>SPACE</kbd> | Scroll up                           |
| <kbd>SHIFT</kbd>+<kbd>TAB</kbd>   | Open tips                           |



## Julia

### Cheatsheets

* <a href="https://cheatsheets.quantecon.org/" target="_blank">Quant Econ cheatsheet for MATLAB, Python, Julia</a>
* <a href="https://juliadocs.github.io/Julia-Cheat-Sheet/" target="_blank">JuliaDocs cheatsheet</a>



## MATLAB

### Cheatsheets

* <a href="https://cheatsheets.quantecon.org/" target="_blank">Quant Econ cheatsheet for MATLAB, Python, Julia</a>



| Syntax                                   | Description                 |
| ---------------------------------------- | --------------------------- |
| <kbd>⌘</kbd>+<kbd>0</kbd>                | Switch to command window    |
| <kbd>⌘</kbd>+<kbd>MAJ</kbd>+<kbd>0</kbd> | Switch to editor window     |
| <kbd>%%</kbd>                            | New code section in .m file |

Run section-by-section ( <kbd>%%</kbd>) without debugger:

-  <kbd>⌘</kbd>+<kbd>Enter</kbd>: Run current section of .m file.
-  <kbd>⌘</kbd>+<kbd>&#8595;</kbd>: Switch sections.

Run section with debugger (code will stop at each breakpoint)

- <kbd>⌘</kbd>+<kbd>ALT</kbd>+<kbd>R</kbd>: Run .m file to next breakpoint
- <kbd>⌘</kbd>+<kbd>ALT</kbd>+<kbd>R</kbd>: Resume running to next breakpoint
- <kbd>MAJ</kbd>+<kbd>fn</kbd>+<kbd>f5</kbd>: Exit debugging mode



## R

| Syntax                | Description                                                  |
| --------------------- | ------------------------------------------------------------ |
| <kbd>getwd()</kbd>    | Displays working directory                                   |
| <kbd>dir()</kbd>      | List files in the current working directory                  |
| <kbd>setwd()</kbd>    | Set working directory                                        |
| <kbd>source("")</kbd> | "loads" the R file into R (useful when you have several functions that you call in the future) |





## Stata

### Stata in Sublime

| Syntax                              | Description                                                  |
| ----------------------------------- | ------------------------------------------------------------ |
| <kbd>control</kbd>+<kbd>D</kbd>     | Do (*echoes the commands as if they were run one-by-one*)    |
| <kbd>control</kbd>+<kbd>R</kbd>     | Run (*silent, runs all the commands at once without displaying them in the command window*) |
| *highlight command* + <kbd>f1</kbd> | Open the Stata help associated with the highlighted command  |



### Stata Editor

| Syntax                                   | Description                            |
| ---------------------------------------- | -------------------------------------- |
| <kbd>⌘</kbd>+<kbd>MAJ</kbd>+<kbd>D</kbd> | Run do-file                            |
| <kbd>⌘</kbd>+<kbd>1</kbd>                | Switch to command window               |
| <kbd>⌘</kbd>+<kbd>9</kbd>                | Switch to editor window                |
| <kbd>⌘</kbd>+<kbd>.</kbd>                | Break                                  |
| <kbd>fn</kbd>+<kbd>&#8593;</kbd>         | Get previous command in command window |



## Sublime Text

| Syntax                                                       | Description                                     |
| :----------------------------------------------------------- | ----------------------------------------------- |
| <kbd>fn</kbd> +<kbd>^</kbd> +<kbd>&#8593;</kbd>/<kbd>&#8595;</kbd> | Previous / next file in side bar                |
| <kbd>⌘</kbd>+<kbd>K</kbd>, <kbd>⌘</kbd>+<kbd>B</kbd>         | Show/hide side bar (need to press K _then_ B!!) |
| <kbd>⌘</kbd> +<kbd>Option</kbd> +<kbd>[</kbd>/<kbd>]</kbd>   | Fold/unfold indented code                       |
| <kbd>⌘</kbd>+<kbd>O</kbd>                                    | Open a whole folder + subfolder                 |
| <kbd>⌘</kbd>+<kbd>K</kbd>, <kbd>⌘</kbd>+<kbd>←</kbd>/<kbd>→</kbd>  <br /><kbd>^</kbd>+<kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd>, ... | Move between file groups                        |



## Terminal

### Ressources

* <a href="https://programminghistorian.org/en/lessons/intro-to-bash#reference-guide" target="_blank">Introduction to bash</a>

| Syntax                                     | Description                                                  |
| ------------------------------------------ | ------------------------------------------------------------ |
| <kbd>cd</kbd>                              | Change directory                                             |
| <kbd>~/</kbd>                              | Shortcut for your home folder address (e.g. "~/Desktop" is "/Users/ycabossi/Desktop") |
| <kbd>cd ..</kbd>                           | Goes back one file in the file path                          |
| <kbd>ls (-la)</kbd>                        | List files in current folder (and display details, like permissions) |
| <kbd>mkdir</kbd>                           | Make directory in the current folder                         |
| <kbd>man *command*</kbd>                   | Manual for the *command*                                     |
| <kbd>touch *FileName.ext*</kbd>            | Create a document in current folder nammed *FileName.ext*    |
| <kbd>open *FileName.ext* (-a *prog*)</kbd> | Open *FileName.ext* with program *prog* (or with default program if no flag specified) |
| <kbd>open .</kbd>                          | Open the current directory in a new window                   |
| <kbd>⌘</kbd>+<kbd>K</kbd>                  | Clear the terminal window                                    |



## Git & Github

### Cheatsheet

| Syntax                               | Description                                                  |
| ------------------------------------ | ------------------------------------------------------------ |
| `git init`                           | create Git repository                                        |
| `git status`                         | check the status of the repository (shows which branch you are on, which commit, untracked files) |
| `git add FILE` </br> `git add --all` | add a specific file or all untracked files to the staging area = include them in the list of tracked files that will be added in the next commit |
| `git commit -m "commit name"`        | commit the tracked files to the current branch and add a name to this commit |
| `git commit -a -m "commit name"`     | add all _and_ commit all untracked files to the current branch |
| `git reset`                          | remove changes from the                                      |



### Ressources

* Introduction to bash: slides from a workshop on Github at Brown.
* Github for economists: slides from Frank Pinter about why use Github for economic research.
* Check also [this chapter] from Jesus Fernández-Villaverde about how to use Git with the command line.
* <a href="https://guides.github.com/introduction/flow/" target="_blank">Github webpage</a> about the workflow in Github (branches, commits, pull requests, merges).
* Check <a href="https://www.toolsqa.com/git/difference-between-git-clone-and-git-fork/#:~:text=When you fork a repository,with the help of Git." target="_blank">this</a> webpage for the difference between forking (copying a repo from GitHub on your GitHub page; inverse: pull request) and cloning (copying a repo from GitHub on your local machine; inverse: push).



###  `.gitignore` files

`.gitignore` files specific intentionally untracked files that Git should ignore. Files already tracked by Git are not affected.

> Ressources:
>
> - `.gitignore` <a href="https://git-scm.com/docs/gitignore" target="_blank">documentation page</a>.
> - `.gitignore`  <a href="https://github.com/github/gitignore" target="_blank">templates</a> (in particular for Stata, MATLAB, Sublime, MacOS).

**ttecon template**

```
# Ignored as it contains user-specific settings
*config_user.yaml

# Ignored as they should contain symbolic links, which are user-specific and can be automatically created via `ttmake`
*external/
*input/

# Ignored as these subdirectories are temporary by design
*temp/

# Temporary files
*temp.*

# Ignored as they contain (links to) large outputs that will be stored outside of Github
# These can be user-specific and can be populated (if already exist) via `ttmake`
*output_local/

# Commit everything in `ttmake`
!*lib/ttmake/

# Ignore thumbnail cache files
._*
Thumbs.db

# Ignore files that might appear on external disks
.Spotlight-V100
.Trashes

Icon?

# Ignore auxiliary files
*.pyc
__pycache__
*.ipynb_checkpoints/
*.lyx~
*.lyx#
*.lyx.emergency
*.Rhistory
*.Rapp.history
*Rplots.pdf
*.DS_Store
Desktop.ini
*.svn
*setup_stata.log
.svn
*.swp
tags
*.swo
~$*.docx
*.acn
*.acr
*.alg
*.aux
*.bbl
*.blg
*.fdb_latexmk
*.fls
*.glg
*.glo
*.gls
*.idx
*.ind
*.ist
*.lof
*.lot
*.nav
*.out
*.snm
*.toc
*.tt
*.ttt
*.brf
*.fff
*.synctex*
*.pdf

# Ignore qsub output files
*.po[0-9]*
*.o[0-9]*
```



###  `.gitattributes` files

`.gitattributes` files tells Git how each file format should be treated when performing git actions, such as `git commit`, etc. In particular, they can separate merge strategies for individual files or directories, tell Git how to diff non-text files, or have Git filter content before you check it into or out of Git.

> Ressources:
>
> - `.gitattributes` <a href="https://git-scm.com/docs/gitattributes" target="_blank">documentation page</a>.
>
> - `.gitattributes`  <a href="https://github.com/alexkaratarakis/gitattributes" target="_blank">templates</a>.
> - <a href="https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes" target="_blank">Customizing Git</a>
> - <a href="https://rehansaeed.com/gitattributes-best-practices" target="_blank">rehansaeed.com</a> 

#### Line Endings

Operating systems use different characters to represent line feeds in text files. Windows uses a Carriage Return (CR) followed by the Line Feed (LF) character (CRLF), while Unix based operating systems use the Line Feed (LF) alone. Newline characters often cause problems in Git when you have developers working on different operating systems (Windows, Mac and Linux).

Git can actually be configured to automatically handle line endings using a setting called autocrlf. This automatically changes the line endings in files depending on the operating system.

```
# Set default behaviour to automatically normalize line endings
* text=auto

# Force bash scripts to always use lf line endings so that if a repo is accessed
# in Unix via a file share from Windows, the scripts will work
*.sh text eol=lf
```

#### Diffing

*Diffing* a file means to run the commands `git diff ` and `diff --git a/worddoc b/worddoc`. It compares the two versions of the files and outputs what has been added or deleted. 

**Example:** `.docx` files are very annoying to diff, and how to even diff an image?
Tell Git to convert these files into a text file or a binary file, and do the comparision of these transformed files (in the case of the image, you will compare the image's metadata). You'll typically need to first install an outside module to extract the appropriate information into a text file (e.g. for `.docx` file, `docx2txt` extracts just the words in the document, for an image, `exiftool` extracts the metadata as text). The `.gitattributes` file then records how to filter these kinds of file before diffing them:

```
*.docx diff=word
*.png  diff=exif
```

The next time you type `diff --git a/image.png b/image.png`, Git will know that it first needs to extracts the metadata into a text file, and only diff these text files.

#### Merging

You can also use Git attributes to tell Git to use different merge strategies for specific files. One useful option is to tell Git to not try to merge specific files when they have conflicts, but rather to use your side of the merge over someone else’s.

```
database.xml merge=ours
```

#### Specifying format

<u>Note:</u> If you're using LFS, the format option is handled by it.

Git is good are comparing two main file formats: **text** and **binary**. You can use `.gitattributes` to tell Git which files are binary (sometimes it can't figure out) and giving Git special instructions about how to handle those files.

Example: If you want to declar `.dta` files as text files, and `.png` files as binary, write

```
# Denote all files that are truly binary and should not be modified
.dta text
.png binary
```



### Git Large Storage Files (LFS)

> Ressources:
>
> -  <a href="https://www.atlassian.com/git/tutorials/git-lfs" target="_blank">Bitbucket help page</a>

Git is a *distributed* version control system, meaning the entire history of the repository is transferred to the client during the cloning process. For projects containing large files (e.g. images, datasets) that are modified regularly, this initial clone (download from GitHub to a local machine) can take a huge amount of time, as every version of every file has to be downloaded by the client.

Git LFS (Large File Storage) is a Git extension that reduces the impact of large files in your repository by downloading the relevant versions of them *lazily*. Specifically, large files are downloaded during the checkout process (the process of switching between commits, branches, or files), rather than during cloning or fetching.

Git LFS does this by replacing large files in your repository with tiny *pointer* files. During normal usage, you'll never see these pointer files as they are handled automatically by Git LFS:

1. When you add a file to your repository, Git LFS replaces its contents with a pointer, and stores the file contents in a local Git LFS cache. 
2. When you push new commits to the server, any Git LFS files referenced by the newly pushed commits are transferred from your local Git LFS cache to the remote Git LFS store tied to your Git repository. 
3. When you checkout a commit that contains Git LFS pointers, they are replaced with files from your local Git LFS cache, or downloaded from the remote Git LFS store.

Git LFS is seamless: in your working copy you'll only see your actual file content. This means you can use Git LFS without changing your existing Git workflow; you simply `git checkout`, edit, `git add`, and `git commit` as normal. `git clone` and `git pull` operations will be significantly faster as you only download the versions of large files referenced by commits that you *actually* check out, rather than every version of the file that ever existed.

**Git LFS and `.gitattributes`:** after installing LFS, you can track `.dta` files using the command `git lfs track "*.dta"`. It will add in the project's `.gitattributes` file the line

```
*.dta filter=lfs diff=lfs merge=lfs -text
```

This lists file extensions for various file types that need to be controlled by Git LFS. It tells Git that these file formats need to be filtered, diffed and mergeed using the LFS tool. Finally, the `-text` argument tells Git that this is not a text file, which is a strange way to tell it that it's a binary file.

<u>Note:</u> You need to make sure that the `.gitattributes` file is being tracked, for that use `git add .gitattributes`.



## Windows

| Syntax                                                       | Description                    |
| ------------------------------------------------------------ | ------------------------------ |
| <kbd>WINDOWS</kbd>+<kbd>TAB</kbd>                            | Go to desktop overview         |
| <kbd>WINDOWS</kbd>+<kbd>CTRL</kbd>+<kbd>&#8592;</kbd>/<kbd>&#8594;</kbd> | Switch between desktops        |
| <kbd>BACKSPACE</kbd>                                         | Previous page in file explorer |

