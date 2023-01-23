# tnproj
tnproj is a development tool for software projects offline.
This project is designed to create serialized project directories for linux users, track tests of their programs, and update them. All of this is done via command line. The program is interactive in nature so as to make it easier to use.
The installation script will setup bin and Template directories if needed, and will install the program files in bin while creating a file structure in Templates to be used by the program. Users can modify the template files and modify the code as needed to suit their needs.
tnproj is the main file of the program and serves to bind the individual modules together.
mkproj is the module responsible for creating the file structure for a project and adding it to a directory contained within the current year's project folder.
testenv is the module responsible for testing a program and recording that interaction in a log.
updateproj is the module responsible for moving a successful testing candidate from the Testing directory to the bin for use on the local system. It's especially useful when writing scripts for personal use.
More modules and improvements on existing modules are planned for the future.
