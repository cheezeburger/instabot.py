# Tutorial

### 1.0 Table of Content
  - 1.1 Installing Python
  - 1.2 Setting up Instabot.py
  
  
## 1.1 Installing Python
### Step 1:
Head over to Python official website to download Python.https://www.python.org/getit/  
You may download any Python version greater than 3. In this tutorial, we will be using Python 3.7. 
**Click on Download Python 3.7.0**
![p1](https://i.gyazo.com/3ef8f59135f7168624eeb8b68801d36c.png)

### Step 2: 
Run the installation file to start installing. Make sure to **check 'Add Python 3.7 to PATH'**  
Uncheck 'Install launcher for all users' if you wish to install for your own profile only.

![p2](https://i.gyazo.com/044462af791d6a7d97482dc27fe3150f.png)


### Step 3:
Once the installation has completed, simply click Close. We will now validate Python installation.  
**While holding the Windows Key, press R** to launch Run. Type in 'cmd' and press OK.

![p3](https://i.gyazo.com/d32dbc239824a8056a8d0b37f3c6d533.png)

### Step 4:
The Command Prompt should now appear. Type 'python' and press Enter.
![p4](https://i.gyazo.com/e0cb23ebb598b665bddc42fdc9c0e6ff.png)

If Python is successfuly installed, you should see something like this. 
![p5](https://i.gyazo.com/b365fff727ad958bd59119cfa115eb2b.png)

Reinstall or modify Python installation if you do not see the above screen.  
Make sure to **check 'Add Python 3.7 to PATH' during installation**.

Congratulations, you have now successfully installed Python to your machine :fire:
___

## 1.2 Setting up Instabot.py
### Step 1:
First, download Instabot.py files at https://github.com/instabot-py/instabot.py
![p6](https://i.gyazo.com/58047d1bfda5e1c09ba14da440efaf6f.png)
**Click 'Clone or Download' and select 'Download Zip'**

### Step 2:
**Unzip/Extract the zip file**.
![p7](https://i.gyazo.com/8a0749bbe8229695e45e417a6e93aa6b.png)
Locate your folder path and change your working directory in the Command Prompt.  
To do this, use the **cd** command. In my case, I placed my unzipped folder on my desktop so my command should look like this  
``cd desktop/instabot.py``

### Step 3:
Type in ``-pip install -r requirements.txt`` and press Enter to install the requirements.  
![p8](https://i.gyazo.com/69452c3b83b563a1284aa9ca4255fb72.png)

Let it download until completion and you should see something like this.
![p9](https://i.gyazo.com/e0697e1d183e02994d84b2d2152f0fd4.png)

### Step 4:
**Navigate to your folder** and **find example.py**. Open the file with any editor.  
In my case, I'll be using NotePad++.
![p10](https://i.gyazo.com/c8c9ef66a83826be49cdb313d7f70604.png)
Look for the following lines of code  
``login="username"``  
``password="password"``  

Where ***username*** is your Instagram username and ***password*** is your Instagram password. **Replace both username and password** and save the file. 

Example:  
![p11](https://i.gyazo.com/e933599efea74f837b8f00262c316436.png)

You may change the other settings such as ``tag_list``  
Where: ``tag_list`` denotes the Tags used to find posts. For this tutorial, we will be using the default settings.  
More info on parameters can be found at the README.md file.

### Step 5:
Here comes the magic. Go back to your Command Prompt, type ``python example.py`` and hit Enter. This is the command to run a Python script.  
If you done everything correctly, the bot should start doing its job!  
![p12](https://i.gyazo.com/98b12adafaa9cf3a1efc4199b9af438f.png)  

___
## Error  
If you receive the following error, simply wait for another 24hrs and try again. It could be Instagram flagging your access due to unknown IP/activity.  
![p13](https://i.gyazo.com/22a463f1deb30a3c3ac4b7f39811b4f0.png)
