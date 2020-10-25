## Hello there we are Matt and Elvis

## This will be how to install python, pip libraries and a virtual environment

<br />

## Step 1:
    1. Install visual studio if you haven't aready at the link provided: https://code.visualstudio.com/download
    2. You can install the extension by typing in python it should be the first item on the. Image below to help:

<br />

## Step 2: 
    1. Install python on your system by visiting the python website: https://www.python.org/downloads/
        * Depending on your system you will need to look at the download options which there will be there for, you also want download the most recent verion of python (currently it is 3.9.0)
        
        * Windows: You have the option to download different versions but the one I used that you can use is Windows x86 executable installer

        * MacOs: When downloading it should be macOS 64-bit installer (Note: this version is for OS X 10.0 and later so make sure your system is compatible)

        * Linux: You will need to get the XZ compressed source tarball file but most recent linux systems have them pre-installed (If not hereis a video to upgrade/download python https://www.youtube.com/watch?v=D_N2K2fTH2M)

<br />

## Step 3 :
    1. Check if it has been installed open the terminal (or command prompt if windows) and type in python3 --version or python --version if you downloaded that version or just python --version or python --version for earlier versions that are on your system

<br />

## Step 4 Downloading pip: (Can skip over if just interested in virtual environment)
    1. To install Pip in python follow the following link above I will explain how to incorporate it in visual studio code
    2. Link:
        * Windows: https://phoenixnap.com/kb/install-pip-windows
        * CentOS 7: https://phoenixnap.com/kb/how-to-install-pip-centos-7
        * Ubontu18.04: https://phoenixnap.com/kb/how-to-install-pip-on-ubuntu
        * Debain 9: https://phoenixnap.com/kb/how-to-install-pip-on-debian-9

    3. The way I did this is
        First: I made sure python is installed in my system by going to the command prompt for windows and typing in python --version in which I got 3.7.9

        Second: I followed the Link to install Pip as that is where we will get all future python libraries (Links provided above, I will be using windows link)

        Third: you want to see if pip already exists in before we move into the installation:
            In the command prompt type in pip help
            If it exists then you will get: a lot of commands that show that pip is ready to use, for your info Pip is automatically installed with python 2.7.9 + and python 3.4 + and also comes with virtualenv & pyvenv virtual environments.

    4. If it is not installed already follow the steps below: 

        Step 1: Got to the link: https://bootstrap.pypa.io/get-pip.py
        and download the get-pip.py file or just right-click and download or save it.
        
        Step 1.5: Save/Download the file in the desire location, What is I saved the file in python file in the Virtual Studio code, you can do the same or somewhere else, it does not really matter as long as you remember where you have it saved.

        Step 2: If at any point you get an error you may need to open the command prompt in administrator mode to allow access, but for now just open up the command prompt:
            * Next, go to the directory of where you get-pip.py is in my case it is in my visual studio code python file. You do this by "cd" to the directory where your file is.
            * Then, once in the directory just type the following:python get-pip.py
            * The following step is to type pip help in the command prompt and a message should show up similar to below:
                pip 18.0 from c:\users\administrator\appdata\local\programs\python\python37\lib\site-packages\pip (python 3.7)
                * The difference will be that it will be your directory followed by pip (python 3.7)

<br />

## Step 5 :
    1.  Here is the sample of how the virtual enivronment was created for visual studio code ( https://code.visualstudio.com/api/extension-guides/virtual-documents ), but I will try my best to explain it for windows users

    2. You should head to the visual studio code and open the project where you want the environment to work (Link : https://code.visualstudio.com/docs/python/python-tutorial)

    3. Then open your visual studio code go to the project, open the terminal and type in or copy and paste
        py -3 -m venv .venv
        .venv\scripts\activate
    4. Then pip install once more to have access to the pip in the virtual environment.


