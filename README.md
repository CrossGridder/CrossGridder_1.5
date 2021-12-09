# CrossGridder_1.2
AudioGridderServer.exe wrapped in a CrossOver 21 Bottle. Goodbye virtual machine, Hello CrossGridder!
**************************************************************************************************
IMPORTANT FOR LINUX USERS: 

There are already a few things that I will be adding to the next PDF guide, especially for Linux. 
Wine configuration "emulate a virtual desktop" must be turned off 
and then open system monitor/processes (I did that on ubuntu studio).

Check that after you launch audiogridder from inside the bottle, 2 audiogridderserver.exe processes are found.
Kill the one with less ram in use, the one with more must be kept running.
I was writing the guide while not confident yet with Linux. I use macOS, but at the end the logic is the same. 

So, if you read this, consider Chapter 6 of the guide obsolete.
*************************************************************************************************

BEWARE. If you have messed a lot with WineHQ, WineBottler and the likes in the past, probably Crossover 
would not work at all because of conflicts in folders and wine prefixes. I also had this problem 
on one of my many setups. It's not even the OS, because I have two machines with the same and on one that
was not heavily tampered with Wine stuff it works, on the other doesnt.

*************************************************************************************************

.. MOJAVE ..
Download CG_1.2_Legacy: https://workupload.com/file/vmrTh8ttVFz

.. CATALINA > MONTEREY / LINUX ..
Download CrossGridder_1.2: https://workupload.com/file/nFCFh23JMU9

.. CHROME OS ..
Not Tested Yet.

.. Download the PDF GUIDE from this repository .. AND READ IT ALL!!!

If one of the files doesn't work on your system try the other. The legacy one is a fix 
to what I think is a gzip issue when decompressing due to the different gzip builds. 
CrossGridder_1.2 was created on Monterey 12.0.1, which is shipped with a higher version.

Please report if you have any issues importing these bottles into CrossOver 21, including your system configuration

Also, please consider donations via Paypal or Brave browser tips when visiting my Github page,
to help me keep this project alive and provide you with new guides,
solutions and bottles for specific configurations
https://www.paypal.com/donate/?hosted_button_id=54VD7JACZSLF2


BELOW IS A PREVIEW OF THE PDF CONTENT

*********************
WHAT IS CROSSGRIDDER
*********************

	. CROSSGRIDDER is an AudioGridderServer.exe wrapped into a Crossover 21 bottle, 
	and its able to do things that AG server can't yet and some others that,
	due to its nature, simply can't be implemented.

	. Follow this whole guide to take advantage of every CrossGridder's feature. 
	I wrote it with one goal in mind:
	provide a comprehensive step by step guide full of details, 
	letting you unleash its full power and capabilities.

	. Being CrossGridder a CrossOver bottle means that VSTs will 	
	work pretty much like native ones. Disabled Sidechain is a current  	
	AudioGridder server limitation.

	. Since version 1.2, it comes in different versions to avoid 	
	importing issues, however, if you have problems importing one, 	
	try the other:

		. CG_1.2_Legacy (Mojave)
		. CrossGridder_1.2 (Catalina > Monterey/Linux)

	. By default It contains freeware softwares. It is up to you to 	
	add more VSTs and build your own dream bottle.

 	. CrossGridder is free and will always be, so please consider a 	
	donation to help me keep this project going on and 	
	be able to technically assist you. 	

	. If none can be imported in your system, please start a discussion
	with your system's details and a brief description of the problem.
  
 ********************************* 
 WHAT CROSSGRIDDER CAN DO FOR YOU!
 *********************************
 
  	.. Be a Linux Server (not available yet as an official AG server):
	. Use VSTs on a Linux machine setup on any Linux DAW that supports the AG plugin. 
	Give a chance to your old PC/Mac installing a Linux distro. 
	If you have an Intel Core processor and a not too old card
	(something like HD 4000 should work), you should be good to go.

	.. Use VSTs on ProTools with the AG AAX plugin

	.. Create as many Servers as your system can handle
	. To overcome AG server limitation of 1 GUI per server.
	. Stop dealing with 2 desktops on 1 screen to see all the GUIs.
	. Stop freezing of a whole chain of plugins if one server freezes. 

	.. Use it a as sandboxed environment for VSTs trial:
	. Do not install the native trial plugin in your OS, install Windows version in CrossGridder.
	. When you decide that the new plugin is worth (or not!) to be 	part of your main system, 
	delete the bottle and install it (or not!) your OS native plugin.
	You can have as many copies of CrossGridder as you wish, 
	so you can even sandbox the sandbox, if you know what I mean :)
	
	.. Or as a replacement for virtual machines on macOS and Linux:
	. Plugins will run pretty much like natives. No CPUs dedicated to virtual machines, 
	less disk space and ram wasted and only one screen to deal with, when used on a one machine setup.
