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



### SSH from a Windows host

### Accessing your office computer via SSH

## High Performance Computing Resources at MSRI

	
