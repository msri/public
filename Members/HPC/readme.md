# Remote Access and HPC at MSRI
---
Remote access to MSRI is granted to all current members. You can continue your remote access beyond your stay at MSRI by coordinating with the MSRI IT Department. Please fill out a [request here](https://app.smartsheet.com/b/form/ee06d2895c2f43c4ac5576d740f40cd7). Be sure to include your name, office number, and the best way to contact you (email, phone, etc.). 

## Remote access via SSH
MSRI does not provide VPN access for members, instead all remote access is achieved via SSH. 
SSH Information:

		Hostname: cycle.msri.org
		User: Your MSRI user ID
		Password: Your MSRI user password
		// The above information can be found in your welcome packet. 
		
### SSH from a Linux / UNIX / Mac OS X host

* Located a Terminal Emulator. In Mac OS, this can be found in Applications -> Utilities - Terminal. 
* SSH using the following command: ssh username@cycle.msri.org, See the screenshot below:
![SSH screenshot](https://s3-us-west-1.amazonaws.com/msri.org/computing/ssh-screenshot.png)
* The default terminal is /bin/sh, you may wish to invoke bash or another more commonly used shell. 
![SSH screenshot bash](https://s3-us-west-1.amazonaws.com/msri.org/computing/ssh-screenshot-bash.png)
* If you intend to run X.org forwarding for graphics support, you will want to use ssh -XY username@cycle.msri.org. This allows the SSH tunnel to utilize your local Xwindows server. This is useful for applications such as: Mathematica, Matlab, and others which require graphics and mouse support. 
* Note for Mac OS X, you will need to install XQuartz. [Download XQuartz here](https://www.xquartz.org/) 

#### Xforwarding on Mac OS X example

1. Install Xquartz (Link above) Alternative: You can use [Homebrew](https://brew.sh/) to install Xquartz with brew install xquartz.
2. SSH to cycle.msri.org using ssh -XY username@cycle.msri.org (See screenshot below). Once you're in the bash prompt, you can start whichever X program you want. Below Mathematica was started to demonstrate X-forwarding. 
![SSH screenshot mathematica](https://s3-us-west-1.amazonaws.com/msri.org/computing/ssh-mathematica.png)



### SSH from a Windows host

* Install PuTTy, [Download Here](https://www.putty.org/)
* Configure putty with the following information ![Putty screenshot](https://s3-us-west-1.amazonaws.com/msri.org/computing/ssh-putty.png)
* Be sure to enter Cycle into the saved sessions region and click "save". This will allow you to "load" future sessions without having to type in the address again. This is all you need to do if you don't intend to use X.org / Graphics support. 

#### Xforwarding on Windows example

1. If you intend to use X.org forwarding for graphics support. Please install, Xming [available here](https://sourceforge.net/projects/xming/).
2. Install Xming using the following configuration options: ![Xming installation](https://s3-us-west-1.amazonaws.com/msri.org/computing/xming-install.png)
3. Open Xming. Xming will show in your system tray. ![Xming screenshot](https://s3-us-west-1.amazonaws.com/msri.org/computing/ssh-xming1.png)
4.  Open Putty and load the Cycle.msri.org from saved sessions. This time, you will make changes to the configuration. Locate the SSH menu from the right navigation pane. Go to X11 and enter the following information: ![X11 forwarding putty](https://s3-us-west-1.amazonaws.com/msri.org/computing/xforwarding-putty.png)
5. Return to sessions and save as the desired session name. Click open and login to cycle.msri.org.
6. After login, you may open the desired X11 application. In this example, Xmaple was invoked: ![Xmaple in Putty](https://s3-us-west-1.amazonaws.com/msri.org/computing/xmaple-putty.png)
7. These are the commands to open popular applications:

		xmaple -nosplash
		mathematica
		matlab
		Xemacs
		kile
		



## High Performance Computing Resources at MSRI

		Still refining documentation for this. 
		Please contact IT support if you wish to experiment with HPC at MSRI. Thank you!
