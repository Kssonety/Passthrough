Please make sure python is installed or else it won't work.

Step 1: Getting python.
        Go to (https://python.org/downloads) and install the newest version of python.

Step 2: Necessary libraries.

These are the libraries needed for the program.
        
          CV2 (OpenCV)
          
          Time (Comes with python)
          
          OS (Comes with python)
          
          Subprocess (Comes with python)
          
          Wallpaper (py-wallpaper)
          
To install a library, use the command : 
          pip install 'library name here'
        
These are the commands :
        
        CV2 : pip install opencv-python
        Wallpaper : pip install py-wallpaper
          
          
Step 3: Python Wallpaper Library Setup.
        Python wallpaper won't work on it's own due to missing files, but let us fix that!

Install the latest release of this repository: https://github.com/sindresorhus/windows-wallpaper/releases

Extract the zip file.
When you are in the extracted folder, you should see two files. (wallpaper.exe and wallpaper.pdb)
Rename them to win-wallpaper.exe and win-wallpaper.pdb

For this you need your PYTHON LIBRARY installation path, to find it open Command Prompt and type:

        where python

It should output a few directories, make sure to use the (\Python\Python311\python.exe) one.
Go to the (\Python\Python311\) and then open the 'Lib' folder.
Now open the 'site-packages' folder, and in there, open the wallpaper folder.

Now you can copy the win-wallpaper.exe and win-wallpaper.pdb to the (\Python\Python311\Lib\site-packages\wallpaper) folder.

And that should all be done!

Now run the python file in the passthrough folder
