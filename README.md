# FacialMotionCapture_v2

## Download trained model (lbfmodel.yaml)
https://github.com/kurnianggoro/GSOC2017/tree/master/data

# Install prerequisites:

## Linux:
(may vary between distro's and installation methods) <br/>
This is for manjaro with Blender installed from the package manager
- python3 -m ensurepip
- python3 -m pip install --upgrade pip --user
- python3 -m pip install opencv-contrib-python numpy --user

## MacOS
open the Terminal
- cd /Applications/Blender.app/Contents/Resources/2.81/python/bin
- ./python3.7m -m ensurepip
- ./python3.7m -m pip install --upgrade pip --user
- ./python3.7m -m pip install opencv-contrib-python numpy --user

## Windows:
Open Command Prompt as Administrator
- cd "C:\Program Files\Blender Foundation\Blender 2.81\2.81\python\bin"
- python -m pip install --upgrade pip
- python -m pip install opencv-contrib-python numpy

## Test Facial Capture
You can use the Test.py script to test facial motion capture.  <br/>
Open the script and change the folder for lbfmodel.yaml to the folder that you downloaded it to.

Then run "python3 Test.py"

