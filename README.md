This project consists of an Iterated function system editor written in Python code in 2015.  I stuck to some basic tools like TKinter.  One of the projects was for my Math 595 computer animation class, but afterwards I tweaked it a bit to allow for some user friendly features.  As of now the project is incomplete (transformation settings in the format menu don't do anything right now), but the generation of iterated function systems employing up to 8 functions is working perfectly well.  

WARNING: this project was made with an old version of python.  some functions might no longer work in newer versions

Current bug to fix: create_square function is often called, but it doesn't clear the undo history, so if you create a new square in the middle of your usage of the function call, you will get your configuration order mixed up. 

EDIT: bug should now be fixed

EDIT 2: clearer documentation added
