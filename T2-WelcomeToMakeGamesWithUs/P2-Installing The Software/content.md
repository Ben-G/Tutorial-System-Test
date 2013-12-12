Step 1: Get Xcode
-----------------
Xcode is to writing apps for iPhone what a word processor is to writing essays. It will format your code, check it for errors, and run it for you. If you already have Xcode, make sure it is version 4.2 or later. Earlier versions won't work. 

If you are running OSX 10.8 or later, get the latest version of Xcode [here](<http://itunes.apple.com/us/app/xcode/id497799835?mt=12/>).

If you are running OSX 10.7 or earlier, first download the free upgrade to OSX 10.9 [right here](<https://itunes.apple.com/us/app/os-x-mavericks/id675248567?mt=12>)

Once it is done downloading, the Xcode application will appear in your applications folder. You can look for it using Spotlight (the magnifying glass in the top right corner).

![image](https://s3.amazonaws.com/mgwu/tutorial/xcodeSpotlight.png)

Step 2: Get cocos2d
--------------------
cocos2d is a game engine that takes a lot of the busywork out of making iPhone games. In the past, you had to write a ton of code to do something simple, like move a character across a screen. cocos2d makes that a breeze! 

[Click here to download the beta version 3.0 of cocos2d](<https://github.com/cocos2d/cocos2d-iphone/archive/develop-v3.zip>)

Step 3: Install cocos2d
-------------------------
Unpack the Zip-File you have just downloaded. Open up the Terminal. Navigate to the cocos2d folder you just have unpacked and execute *install.sh*:

	Example:    
	$ cd cocos2d-iphone
	$ ./install.sh

In case you are running Xcode at the moment - restart it now, so that the new cocos2d templates are loaded.