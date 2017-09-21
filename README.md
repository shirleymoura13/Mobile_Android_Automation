# Mobile_Android_Automation
Mobile_Android_Automation

README

This README would normally document whatever steps are necessary to get your application up and running.

What is this repository for?

Quick summary for Tests
Version - 1.0
Pre Requirements:

install Vysor (Cell phone e Desktop);
install Android SDK (https://developer.android.com/studio/index.html)
copy sdk from(C:\Users\Seu_Usuario\AppData\Local\Android) to C:(renomeando para android-sdk)
include in environment variables(Path): C:\android-sdk\tools\bin C:\android-sdk\tools C:\android-sdk\platform-tools
include in user variables: ANDROID_HOME - C:\android-sdk
to confirm the instalation, type on cmd: adb version (it brings the sdk installed version) "Android Debug Bridge version 1.0.39 Revision 3db08f2c6889-android Installed as C:\android-sdk\platform-tools\adb.exe" On cmd, type: uiautomatorviewer (Will open UI Automator Viewer)
Obs: In case of error when trying to connect the dispositive {unable to connect to adb. check if adb is installed correctly.} On the archive uiautomatior.bat, change the line: [call "%java_exe%" "-Djava.ext.dirs=%javaextdirs%" "-Dcom.android.uiautomator.bindir=%prog_dir%" -jar %jarpath% %*]

to: [call "%java_exe%" "-Djava.ext.dirs=%javaextdirs%" "-Dcom.android.uiautomator.bindir=C:\DEV\androidSDK\tools" -jar %jarpath% %*]

Install Java SDK (8)
Install Ruby & Devkit (validate the installation: ruby -v)
Install Cucumber: gem install cucumber
Install Genymotion.
Install Appium lib: gem install appium_lib
Install Appium: ( appium-desktop-Setup-1.2.0-beta.3.exe)
Install Sublime Text 3
Contribution guidelines

Writing tests
Code review
Other guidelines
Who do I talk to?

Repo owner or admin
Other community or team contact
