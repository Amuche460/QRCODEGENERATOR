# QRCodeGenerator

PROJECT TITLE </br>

QRCodegenerator V1

DESCRIPTION</br>
The QRCode Generator is a GUI program to generate QRCodes based on some user metrics. These metrics are the user's full name, email address, website address and phone number. Furthermore, the program asks the user to input the name of the file with the svg file extension. The current version is version 1.0 but more features will be added soon.</br>

USAGE</br>
STEP 1: When the application loads, you will see the Graphical User Interface (GUI) as shown below:</br>
![QRCode](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/d2d88df9-90af-49ef-ae0c-c73b2615190c)

STEP 2: Input your Full Name, Email Address, Website, and the name of the svg file in each field's respective textbox (See Figure 1 above)</br></br>

STEP 3: Click the Click to Generate button to generate the file in the current directory where the python file is executed from (Figure 2)</br></br>

ERROR CORRECTION</br>
As with any good program, each input is checked first before  generating the QRCode.</br>
![errorcatcher](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/10b540e0-5b31-451d-897f-a322bd52990e)

VERSION UPDATE</br>
The version is QRCode Ver 1 and any update will be shown here.  </br>

DEPLOYMENT</br>
To run this file, make sure that python is installed (Using Python 3.9 or more) and press F5 using IDLE IDE. But any IDE like Visual Studio Code or any IDE will do.
To convert to an executable (.exe), you have two options: </br>
STEP 1: First install pyinstaller via the command line or terminal by typing...pip install pyinstaller</br>

STEP 2: Type the following in the command line</br>
pyinstaller --onefile --windowed --add-data "xi.icon;" qrcodegenerator.py

STEP 3: Allow pyinstaller to compile the file and add all the resources and dependencies needed to create the executable.</br>

STEP 4: Check the folder and run the exe in another computer. It will successfully run</br>

Alternatively (and even better option), you can use auto-py-to-exe to generate the executable. This normally opens a GUI for compiling your programs. First install auto-py-to-exe by typing the following in the commandline: pip install auto-py-to-exe and then follow the steps as shown below:</br>

![i](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/9d574b6c-5248-4a64-81c9-045f740f7ff6)

Notice that python39.dll was added. This will help run the program in older versions of Windows eg Windows 7, 8, 8.1 (probably they have not been updated for a long time. This will avoid generating errors such as the one shown in issues section).</br> 

ISSUES</br>
Please note that your Windows Defender Antivirus (and some other antimalware programs) may block the application from running. This is a false positive error message. Kindly pause the protection for a while and run again
The dependency python39 must be added to avoid errors such as the one shown below:</br>

![python39 error](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/7e5dc13c-4a0f-485b-b97e-ce1ae34e3fc4)

The python39 is saved in the AppData folder. As shown in the image below:</br>
![python39](https://github.com/Amuche460/BMICALCULATOR/assets/143182420/e1f23b6d-f9f0-4446-83b2-03c7666c14fe)




