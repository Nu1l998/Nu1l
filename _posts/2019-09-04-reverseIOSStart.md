---
title: Reverse IOS Start
tags: Reverse
key: Page_ReverseIOSStart
show_edit_on_github: false
---

Why I Wrtie this ?
{:.warning}


Cause my work's need,I have to work this thing.(Do not ask me what im I doning),
So I write this md voluntarily to help others to have his first setp into this mysterious things.
{:.success}

## 0x0  Connect to Ur Device

	we need to prepare some Tools on Mac to connect to Ur Apple devices

* 1.U need to root your Apple Device Firstly! 
	
	* I think you'll love this tool : www.i4.cn for his OneKeyRoot! 
* 2.Install Cydia on your Device & learn to use it. 
* 3.Install OpenSSH Plug-in on your Cydia. 
* 4.Then you should to reMap the USB to a port. 

	We Use USBSSH/ tool to make it

	`Terminal:`{:.info} 

	> /USBSSH/tcprelay.py -t 22:2222

	use this command to remap 22 to 2222 
	so you can surely ssh to 2222 to connect Ur Apple devices

	`Terminal:`{:.info} 
	
	>ssh root@localhost -p 2222

* 5.Then Write "alpine" on your mind this is the default PsWd to ur Apple devices
	
	Ok until here you can use your Apple devices like a linux System

	
## 0x1  Make up you own environment.
	Ok Then you need to Install some soft for Reverse !

* 1.IDA (someone like Hooper ,but it very slow!)
* 2.iFunBox (a Tool like iTunes but we can assess to the root dir) 
	
	- ps: if you like scp you can choose it 
* 3 Xcode if you system not support high version install 9.4 is ok
	
	- download it from apple.com
* 4 brew
	- many tools will install by it ,just like apt-get in ubuntu
	- by the way install "ldid" we'll use it after  

* 5.LLDB 

	Ok,it's a very long way to install it 
	There just show the html :[ LINK](https://www.cnblogs.com/ludashi/p/5730338.html)

	`!!!Attention:`{:.warning}
	you should give Debugserver exec permission on your devices 
	
	Here is a Demo to local Breakpoint on your App proc:[ LINK](https://www.jianshu.com/p/89813c1323fb l)

	`!!!Listen!!! :`{:.warning}
	you had better have some assembly knowledge Or you will feel `very*N` hard!

<!--more-->

`Enjoy It`{:.error}


