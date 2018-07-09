# GDP_XY_plots
Code to read World Bank GDP data and create some basic XY plots.
# Installing Python 3
Install python 3. 
Preffered Method: 
python3 with anaconda(https://www.anaconda.com/download/#macos)
#
OS X: 
http://docs.python-guide.org/en/latest/starting/install3/osx/
#
Windows: 
http://docs.python-guide.org/en/latest/starting/install3/win/
#
Linux: 
http://docs.python-guide.org/en/latest/starting/install3/linux/
# Installing pygal
*Pip is sometimes included automatically when Python is installed to your system, and sometimes you have to install it yourself. 
If you do not have pip*
OS X: 
1. open terminal
2. sudo easy_install pip
#
Windows: 
1. To install pip, go to https://bootstrap.pypa.io/get-pip.py. Save the file if you’re prompted to do so; if the code for get-pip.py appears in your browser, copy and paste the entire program into your text editor and save the file as get-pip.py.
2. Open command prompt and navigate to the folder containing get-pip.py 
3. python get-pip.py
#
Linux: 
1. To install pip, go to https://bootstrap.pypa.io/get-pip.py. Save the file if you’re prompted to do so; if the code for get-pip.py appears in your browser, copy and paste the entire program into your text editor and save the file as get-pip.py.
2. Open a terminal and navigate to the folder containing get-pip.py
3. sudo python get-pip.py
#
Type "pip install pygal". For more information about pygal, http://pygal.org/en/stable/installing.html.
# Running Code
Preffered Method: open Spyder from anaconda. Spyder is open source IDE that automatically comes with several scripting libraries.
#
OS X: 
1. Create a folder to run code in this repo. Download the code and csv files and move it to this folder.
2. Open Terminal.
3. cd to the folder
4. Type "python ./csvread.py" to run this program. 
NOTE: If you have python 2 and python 3 installed run "python3 csvread.py"
#
Windows:
1. Create a folder to run code in this repo. Download the code and csv files and move it to this folder.
2. Open Command Prompt.
3. cd \ to the folder
4. Type "csvread.py" to run this program. 
NOTE: If it didn't work, make sure your PATH contains the python directory.
#
Linux: 
1. Create a folder to run code in this repo. Download the code and csv files and move it to this folder.
2. Open up the terminal program. In KDE, open the main menu and select "Run Command..." to open Konsole. In GNOME, open the main menu, open the Applications folder, open the Accessories folder, and select Terminal.
3. cd ~/ to the folder
4. Type "chmod a+x csvread.py" to tell Linux that it is an executable program.
5. Type "./csvread.py" to run this program. 
