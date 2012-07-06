Phonegap Android Template
=========================

### Installation guide
	$ install maven3
	$ install android sdk
	$ configure avd (android 2.3.3)
	$ export ANDROID_HOME to your sdk path
	$ run ./thirdparty-install.sh to install Apache Cordova
	$ run your emulator
	$ mvn clean install android:deploy
### How to remove app from emulator
	$ adb shell
	$ cd /data/app
	$ rm ***.apk
	$ exit
	$ restart emulator
	
### How to view emulator's log
	$ adb logcat