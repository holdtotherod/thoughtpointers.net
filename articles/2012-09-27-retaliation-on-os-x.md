title: Retaliation on OS X 10.8

Retaliation on OS X 10.8
------------------------

Just got my [Dream Cheeky USB Rocket Launcher](http://www.dreamcheeky.com/thunder-missile-launcher). The end goal is to hook it up to my [Raspberry Pi](http://www.raspberrypi.org) and leverage the [Retaliation](https://github.com/codedance/Retaliation#readme) script to punish me or my cube mate if we break the build. But of course, I wanted to test it out at home first. So I hooked it up to my iMac. Here's all the necessary commands to get it running on OS X 10.8 Mountain Lion (I'm assuming you have Homebrew installed, but not pip).

	brew install libusb
	sudo easy_install pip
	sudo pip install pyusb
	wget https://raw.github.com/codedance/Retaliation/master/retaliation.py
	chmod +x retaliation.py
	./retaliation.py will

Thanks to ITR8R for the [original inpiration](http://itr8r.tumblr.com/post/31840231144/raspberry-pi-retaliation)!
