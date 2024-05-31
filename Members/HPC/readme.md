# Remote Access and HPC at SLMath
---
Remote access to SLMath is granted to all current members. You can continue your remote access beyond your stay at SLMath by coordinating with the SLMath IT Department. Please fill out a [request here](https://SLMathhelpdesk.freshdesk.com/support/home). Be sure to include your name, office number, and the best way to contact you (email, phone, etc.). 

## Remote access via SSH
SLMath does not provide VPN access for members, instead all remote access is achieved via SSH. 
SSH Information:

		Hostname: hpc.slmath.org
		User: Your SLMath user ID
		Password: Your SLMath user password
		// The above information can be found in your welcome packet. 
		
### SSH from a Linux / UNIX / Mac OS X host

* Locate a Terminal Emulator. In Mac OS, this can be found in Applications -> Utilities - Terminal. 
* SSH using the following command: ssh username@hpc.SLMath.org.
* The default terminal is /bin/sh, you may wish to invoke bash or another more commonly used shell. If you want to make permanent changes to your shell: edit ~/.profile to invoke the shell of your choice.
* If you intend to run X.org forwarding for graphics support, you will want to use ssh -XY username@cycle.SLMath.org. This allows the SSH tunnel to utilize your local Xwindows server. This is useful for applications such as: Mathematica, Matlab, and others which require graphics and mouse support. 
* Note for Mac OS X, you will need to install XQuartz. [Download XQuartz here](https://www.xquartz.org/) 

#### Xforwarding on Mac OS X example

1. Install Xquartz (Link above) Alternative: You can use [Homebrew](https://brew.sh/) to install Xquartz with brew install xquartz.
2. SSH to cycle.SLMath.org using ssh -XY username@cycle.SLMath.org

## High Performance Computing Resources at SLMath

		We are still refining documentation for this. 
		Please contact IT support if you wish to experiment with HPC at SLMath. Thank you!
