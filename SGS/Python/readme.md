# Installing Python before your visit to MSRI
---
These instructions tell you how to install python 3 via Anaconda. These instructions are universal for Mac OS X, Windows, and Linux.

If you have problems, please email: itsupport at MSRI.ORG. More info is available here:

[Specific instructions for Mac OS X](https://docs.anaconda.com/anaconda/install/mac-os)

[Specific installation steps for Linux](https://docs.anaconda.com/anaconda/install/linux)

[Specific installation steps for Windows](https://docs.anaconda.com/anaconda/install/windows)

		
### Installing Anaconda

* Download Anaconda [here.](https://www.anaconda.com/download)
* Be sure to download Python 3.6 (Not Python 2.7).  
* Click on the 64-Bit Graphical Installer. The download will begin. 
![64 Bit Installer Screenshot](https://s3-us-west-1.amazonaws.com/msri.org/computing/python-3.6.png) 

* Begin the installation by double-clicking the downloaded file. 

* Click next at the Welcome to Anaconda3 screen:

![Python Welcome](https://s3-us-west-1.amazonaws.com/msri.org/computing/welcome-python.png)

* Click agree to the license agreement screen: 

![License Agreement screen](https://s3-us-west-1.amazonaws.com/msri.org/computing/license-python.png)
* Choose the default option for installation type:

![Installation type](https://s3-us-west-1.amazonaws.com/msri.org/computing/installation-type-python.png)
* Choose the default location for installation location:

![Installation location](https://s3-us-west-1.amazonaws.com/msri.org/computing/destination-python.png)
* Choose the following under advanced options and Click Install:

![Advanced options](https://s3-us-west-1.amazonaws.com/msri.org/computing/advanced-python.png)

* Once the installaton completes, click Next.
* Click on the Install Microsoft VSCode. 

![Install vscode](https://s3-us-west-1.amazonaws.com/msri.org/computing/install-vscode-python.png)
* Once the VSCode installation has completed. Click Next, then click Finish. 
* You're now ready to test your installation.

### Testing your Python installation

* Locate and open Anaconda Navigator.
* The first time running will ask whether you want to help improve Anaconda. This is up to the end-user whether they want to check yes. Click "OK, and don't show again"
* Locate Jupyter Notebook and click launch:

![Jupyter](https://s3-us-west-1.amazonaws.com/msri.org/computing/jupyter-notebook.png)

* Select new from the top right side of the screen. Choose Python 3. 

![Python 3 new](https://s3-us-west-1.amazonaws.com/msri.org/computing/new-python-3.png)

* You should see this following: 

![Untitled in prompt](https://s3-us-west-1.amazonaws.com/msri.org/computing/Untitlied-in-prompt.png)


* For the following statement, ensure the cell is evaluated as "Code" and not "Markdown" Try testing some NumPy features:
		
		import numpy as np
		print(np.__version__)
		
* Evaluate the above code by hitting Shift + Enter at the same time.

The above code should print:

![Print NumPy](https://s3-us-west-1.amazonaws.com/msri.org/computing/print-numpy.png)
		


* You have successfully tested your Python Installation. 
