Step 1: Create a new Project in Xcode
-----------------------------------------
Open Xcode and select File->New->Project... from the top bar:

![image](https://s3.amazonaws.com/mgwu-misc/cocos2d-3-tutorials/FirstProject/xcode_new_project.png)

Xcode will open a new project and you will get to choose a template for it. In the left navigation box you should see a section called *cocos2d v3.x*. Select that section, than selected *cocos2d iOS* from the right section. Finally hit the *Next* button:

![image](https://s3.amazonaws.com/mgwu-misc/cocos2d-3-tutorials/FirstProject/new_cocos_project.png)

Now you get to choose a project name. How about *HelloMGWU*? 
Finally select a folder for your project.

Now you should see an Xcode project that contains some files and folders:
 
![image](https://s3.amazonaws.com/mgwu-misc/cocos2d-3-tutorials/FirstProject/cocos_template_xcode.png)


Step 2: Run it!
---------------

![image](https://s3.amazonaws.com/mgwu-misc/cocos2d-3-tutorials/FirstProject/run_xcode.png)

Make sure you have your project selected in the drop down menu next to the run button. Make sure that you have the iPhone simulator selected in the next drop down menu over. Hit run! The iPhone simulator should come up and you should see the following:

![image](https://s3.amazonaws.com/mgwu-misc/cocos2d-3-tutorials/FirstProject/run_app_simulator.png)

Common Issues Running for the First Time
----------------------------------------

Permissions Errors?
===================
If you're seeing something in Xcode when trying to run your project saying that it couldn't create a directory or permission was denied and the directory listed contains '/DerivedData', you can solve the problem by going into Xcode Preferences > Locations and change Derived Data to Relative. Enter 'Data' in the text field and you should be all set. Try running your project again.

Still won't work?
=================

Get in touch with us by chatting with us at the bottom of the screen or posting the help section of our forums! 