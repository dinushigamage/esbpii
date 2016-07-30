# ESBPII - Lab 01/ 02
<center>![](http://i.imgur.com/zcmWpFi.png) </center>

# <center> Sri Lanka Institute of Information Technology </center> #

## <center>Enterprise Standards and Best Practices for IT Infrastructure </center> ##

### <center>4th Year 2nd Semester 2016 </center> ###

### <center>Creating Windows and Linux Instance using AWS account </center> ###











#### <center> *SLIIT ID: IT13049096* </center>  ####

#### <center> *Name: Dinushi Madurangi G.G.* </center>  ####

#### <center> *Practical Session: WD * </center>  ####

----------

#### <center> Creating Windows Instance using AWS account. </center>  ####

* First user has to login to the AWS account using correct username and password.

![](http://i.imgur.com/Cw6yg87.png)

* Then select EC2 tab to create a new instance.

* Then click “Launch Instance” button and from the list of AMI s appeared on the screen select “Microsoft Windows Server 2012 R2 Base” AMI to create windows instance.

![](http://i.imgur.com/g6zoCRo.png)

* Select the default instance type given and click “Preview and Launch” button.

![](http://i.imgur.com/VrtXvFJ.png)

![](http://i.imgur.com/YKF7FZi.png)

![](http://i.imgur.com/cY76oYv.png)

* Then after creating the instance next step is reviewing the instance created. Click the “Launch” button to continue.

![](http://i.imgur.com/bZ4BfJr.png)

* Next user has to create a new key pair to launch the newly created instance by providing a name to the key pair.

![](http://i.imgur.com/UPtOugF.png)

* Next click “Download Key pair” button to download the key pair to your system and “windows.pem” file will be downloaded. 

![](http://i.imgur.com/ROvm4fZ.png)

* Then created instance will be launched as shown below and click the “View instance” button to view the instance you created. 

![](http://i.imgur.com/i9e4BPZ.png)

* Then to connect to the instance click “Connect” button. To get connect to the instance first user should get a password 

* Next to get the password should provide the path of “windows.pem” file and decrypt the password. 

![](http://i.imgur.com/Pmf8ot3.png)

* Then user can get the password to access the instance and click “Download Remote Desktop File” button to download the file. 

* Then double click the downloaded file and user has to provide the password received from the previous step to connect to the instance. 

![](http://i.imgur.com/CggcWtL.png)


* Click “Yes” to continue.

* Then user can access to the created Windows instance AMI. 

![](http://i.imgur.com/5IfAAhc.png)

* Finally select the “Instance state” and “Terminate” the Instance.

![](http://i.imgur.com/Lr7kfjr.png)


----------

#### <center> Creating Linux Instance using AWS account. </center>  ####

* First user has to login to the AWS account and then click “Launch Instance” button and from the list of AMI s appeared on the screen select “Amazon Linux AMI 2016.03.3 (HVM)” AMI to create linux instance. 

![](http://i.imgur.com/hps8di9.png)

* Select the default instance type given and click “Preview and Launch” button. 

![](http://i.imgur.com/qZQFgmk.png)

* Then after creating the instance next step is reviewing the instance created. Click the “Launch” button to continue. 

![](http://i.imgur.com/CpBAPcz.png)

* Next user has to create a new key pair to launch the newly created instance by providing a name to the key pair and then click “Download Key pair” button to download the key pair to your system and “linux.pem” file will be downloaded. 

![](http://i.imgur.com/EQk2jk4.png)

* Then created instance will be launched as shown below and click the “View instance” button to view the instance you created. 

![](http://i.imgur.com/RuwupoJ.png)

* Then download putty.exe and puttygen.exe files. 

![](http://i.imgur.com/DyupktV.png)

* Next open the puttygen.exe file and click “Generate” button to get the putty key. Under type of key to generate, select SSH-2 RSA. 

![](http://i.imgur.com/330xxuu.png)

* Click “Load” button and locate “linux.pem” file and click “Open”. 

![](http://i.imgur.com/lGb3KvE.png)

![](http://i.imgur.com/DRmfiW5.png)

* After generating the putty key it should be saved by clicking “Save Private Key” to use it in putty. Click “Yes” to continue and define the place where the putty key should be saved. 

* Then open the putty.exe file to connect to the linux instance and give the public DNS as hostname and provide a name to save the creating session and click “Save”. 

![](http://i.imgur.com/VAigHdU.png)

* Then go to Connection- SSH – Auth to control SSH authentication.

![](http://i.imgur.com/sH0fKqB.png)

* Then locate the saved private key to start the linux instance with putty.

![](http://i.imgur.com/htjWEiw.png)

* Then the console will appear and user has to login as “ec2-user” to launch the Linux AMI instance.

![](http://i.imgur.com/Xho2aMB.png)

* Terminate linux instance.

![](http://i.imgur.com/sJyAlzb.png)
