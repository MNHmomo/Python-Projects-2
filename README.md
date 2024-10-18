# Python-Projects-2
A second set of projects made in Python.

STL Viewer
  An application to view '.stl' files in a 3D environment.
  Choose a '.stl' file, upload it, and customize it.
  When you upload the file, it shows a preview of what it will look like when you open it.
  Customization includes mesh type and color so far.
  This program combines the "PyVista" and "Tkinter" libraries to make a functional GUI application.

Port Scanner
  Includes the "Socket" library.
  Includes "Tkinter" library for GUI.
  Automatically attaches to the host network and IP of the device running the program.
  Scans open ports on the network, displays which ports are open, and displays what banner information that port has.
  Tested on both MacOS and Windows; Runs significantly smoother on MacOS, runs a lot slower on Windows.
  Still much room for improvement regarding efficiency.
  Although as a basic port scanner, it does its job.

Text File Handler
  Basic ".txt" file handler.
  Type in the desired name of the file, and the desired contents of the file, and it creates a ".txt" file with that name and content.
  Saves them in JSON so even if the program were to close and open up, it would save progress.
  No delete or edit option yet.
  Combines with GUI.
