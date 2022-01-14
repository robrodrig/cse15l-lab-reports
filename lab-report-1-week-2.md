
# Week 2 Lab Report

## Topic of discussion: Remote Access

Good Afternoon Audience. In this tutorial, you will see how to log into your course-specific account in a **step-by-step** process! (I know, very exciting stuff)

```
Disclaimer 
This tutorial is for Windows 10 operating sytem
based computers.
```

## Instal VS Code

Installing **VS Code** on your computer is as easy as 1-2-3. 

Go to [Visual Studio Code website](https://code.visualstudio.com/) & follow all the directions listed to download and install on your computer. 

**Note**: Make sure to install the version *specific* to your computer. In this case
you will download the Windows installer.

```
If you have any errors, reach out and ask! 
We would love to help!
```

After the install completes, VS Code should look like this on your desktop.

![Image](./screenshots/vscode.PNG)


## Connecting Remotely

As I touched on earlier, you'll have a CSE course specific account to login to once you have the necessary software needed to connect remotely using VS Code on your computer.
For this step, you'll have more installations of software to complete.

You'll need to install [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)

The link will show how to install the necessary software packages for Windows onto your computer. Stop following the steps before the doc begins explaining the SSH Server process. That will not apply for this lab.

Once this is completed, you'll want to look up your course specific account I keep mentioning [here](https://sdacs.ucsd.edu/~icc/index.php)


Now, we will be connecting to the UCSD servers from your computer using VS Code. 

We will be connecting using the terminal in VSCode, however there is the option to use the remote option as seen in a how-to here: [VS Code Site](https://code.visualstudio.com/docs/remote/ssh#_connect-to-a-remote-host). 

Now you will need to type your course specific account (in place of the 'qq' I have in my example.)

```
cs15lwi22qq@ieng6.ucsd.edu
```

Type the *ssh* command from your terminal to begin the connection:
```
ssh cs15lwi22qq@ieng6.ucsd.edu
```

The terminal will look like this after connecting:

![Image](./screenshots/remoteconnect.PNG)

There is a small change here:

During connection for the first time, you will be prompted by a yes/no question like this:

```
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```

Type yes to agree, then you will be prompted for your password. Enter your password and you should be connected like seen in the screenshot above!













![Image](./screenshots/sshot.PNG)
