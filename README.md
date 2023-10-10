# jupyter-st3-pymolpysnips

# Purpose

A PyMOL Python snippet library to edit live Jupyter notebook cells with Sublime Text 3 using GhostText.



## Installing and using snippets with Sublime Text 3
The snippets are stored in separate files with the file extension `.sublime-snippet`.

For to install the snippets via the Sublime Text's GUI (Mac, Windows, Linux), go to Preferences→Browse Packages...→User→snippets. 
You may need to create the subdirectory called snippets. 
Copy and paste the folder `st3pymolpysnips` into the snippets folder.

To install the snippets on the command line on macOS, create the snippets directory in the Sublime Text3 folder: 

```bash
mkdir ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/snippets/
```
Move the `st3pymolpysnips` folder into the snippets folder.

```bash ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/snippets/
mv st3pymolpysnips ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/snippets/.
```
## Note

Some snippets depend on some pymolshortcuts.
Add the [pymolshortcuts.py](https://github.com/MooersLab/pymolshortcuts) file to your working directory.
