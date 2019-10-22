## How to:

### Clone the repo

### After cloning the repo on the machine you would like to run the XML files on, make sure that node is installed on the machine.

### Restart the machine after installing node.

### run npm install to install the packages required. 

### run using node index.js

NOTE:

If you are adding the project to a machine with no internet, do the following:

Add the node installer.exe to the machine. Run the installer. Make sure that "Add to Path" is a selected option.

After installation is complete, restart the machine.

Move the node files from C:\Users\%username%\AppData\Roaming\npm-cache on the machine with internet to 
the same location on the machine without internet.

Run npm install to install your node files before packing, in the directory of the project folder. 

Create a tarball with npm pack.

Copy the tarball over to the machine without internet connection.

Install the modules with npm install <filename>.

### If you want the program to start automatically when windows starts up:

add the "StartXML.bat" to the startup folder of windows. 