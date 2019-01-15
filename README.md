# MacPuttyPort
To successfully install PuTTY, xCode, MacPorts, and xQuartz must be installed on the machine. 

The first segment of the shell will prompt the user to install xCode if not detected on the machine. When xCode is on the machine, xCode Command Line Tools will be installed. In addition, xCode will ask the user for their credentials to accep their license agreement of usage. 

Note: xCode will not be automatically installed. xCode is one of Apple's Developer Tools that must be downloaded from their site. The user may also download the command line tools through Apple's Developer Website. 

The second segement of the shell consists of the automatic installation of MacPorts from <https://www.macports.org/install.php> The shell will display a prompt asking the user to select which operating system (codename) they currently have installed on their machine. 
![MacPortImage](https://github.com/ggiande/putty-example/blob/assets/macports.png?raw=true)

The third segement of the shell will automatically install xQuartz from <https://www.xquartz.org/>. xQuartz is an open-source effort to develop a version of the X.Org X Window System that runs on OS X, and will also prompt the user for their password to install xQuartz. After the installation of xQuartz is completed, the shell create a local desktop shortcut that will open PuTTY.



