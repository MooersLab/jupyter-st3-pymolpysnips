# jupyter-st3-pymolpysnips

## Purpose

A PyMOL Python snippet library to edit live Jupyter notebook cells with Sublime Text 3 using browser plugin [GhostText](https://ghosttext.fregante.com/) and the [Ghost Text plugin for Sublime Text 3](https://forum.sublimetext.com/t/ghosttext/13734). 
The later plugin links a server in Sublime Text 3 with any text area in the web browser including jupyter notebooks.
This snippet library include snippets for loading PyMOL's Python API into an active Jupyter notebook.

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
