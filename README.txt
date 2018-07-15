To install pygtk dependencies on Windows 64 by hand, do the following:

Clone this project into a directory. Once you got all the files,

Install python 2.7

Extract gtk+ bundle. Set path to its bin directory. (c:\somewhere\gtk+-bundle_2.22.1-20101229_win64\bin)

Test by tying a command: gtk-demo

Add the following bindings (see below):  pygobject, pygtk, cairo

C:\Users\peterglen\Downloads>python -m pip install pygobject-2.28.6-cp27-none-win_amd64.whl
Processing c:\users\peterglen\downloads\pygobject-2.28.6-cp27-none-win_amd64.whl
Installing collected packages: pygobject
Successfully installed pygobject-2.28.6

C:\Users\peterglen\Downloads>python -m pip install pygtk-2.22.0-cp27-none-win_amd64.whl
Processing c:\users\peterglen\downloads\pygtk-2.22.0-cp27-none-win_amd64.whl
Installing collected packages: pygtk
Successfully installed pygtk-2.22.0

C:\Users\peterglen\Downloads>python -m pip install pycairo_gtk-1.10.0-cp27-none-win_amd64.whl
Processing c:\users\peterglen\downloads\pycairo_gtk-1.10.0-cp27-none-win_amd64.whl
Installing collected packages: pycairo-gtk
Successfully installed pycairo-gtk-1.10.0

Now PyGtk should be operational.