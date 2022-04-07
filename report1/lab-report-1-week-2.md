# **Lab Report 1**

___

## Installing VS Code
Visual Studio Code is the text editor we will be using in this class. It is important to have this installed so that you will be able to follow along more easily and have a comfortable environment to write your code in.

1. Go to the [VS Code Website](https://code.visualstudio.com/) and download the VS Code Installer using the button below. ![VS Code Download](VSCodeDownload.png)

2. After the download has completed, double-click the executable file in order to run the installer. 

3. Follow the instructions given by the installer in order to set up VS Code. 

4. Once your setup is complete, you should see VS Code pop up looking something like this. ![VS Code App](VSCodeApp.png)

For now, this is all you need to do. Opening and editing programs on VS Code is fairly easy (just click File>Open), but we will go over the process later, as needed. 
___

## Remotely Connecting
Connecting your personal computer to remote servers is an important part of this class and necessary in order to complete tasks. Here is how you would connect your computer to a server space. 

1. Before you start trying to connect to the server, you need to find your account. Use [This Link](https://sdacs.ucsd.edu/~icc/index.php) to search up your account. 

2. Under Account Lookup, enter your information (your Student AD Login username and your Student ID) and click on the Submit Query Button. ![Account Lookup](AccountLookup.png)

3. Under the Additional Accounts section, note your account username. Specifically make sure to remember the last 3 characters at the end. ![Account](AccountDetails.png)

4. Now, open up your terminal. It should look something like this: ![Terminal](Terminal.png)

5. Type `ssh cs15lsp22zz@ieng6.ucsd.edu` into the Terminal. Replace the `zz` in the command with your own username that you found earlier on Account Lookup. After putting in your own username, click enter to run the command. 

6. Once you have ran the ssh command, you will be prompted to enter your password. Type in your password and click enter. 

7. After clicking enter, you should see a screen similar to the following. If you can see this, move on to the next section. ![SSH Terminal](SSHSuccess.png)

8. TroubleShooting:  If you are unable to see this, make sure you typed in the `ssh` command, your username, and your password correctly. If this does not work, you may have to go back to [Account Lookup](https://sdacs.ucsd.edu/~icc/index.php) and change your password. 

___

## Trying some Commands
Command Line is a useful tool that is required in order to control actions within the server. Here are some commands that you can use in order to navigate the server's directory and do other cool functions.

___

## Moving files with `scp`
`scp` is a useful command that can help us move files from our local system to the server. Using it is necessary in order to transfer important files (such as code) between systems. 

___

## Setting up an SSH Key
Constantly typing in your password in order to connect with your system is annoying. We can create an SSH Key to essentially "register" your personal machine with the server and make sure it no longer requires you to type in your password. 

___

## Optimizing Remote Running
You might have noticed that, even with the SSH Key, it still takes quite a few commands to even do the most basic tasks. Here are a couple of ways you can optimize this process.

___