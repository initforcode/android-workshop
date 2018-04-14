# android-workshop

## Android Workshop Schedule 

1. Introduction to Android Studio 
	* Java 
	* XML
	* Activity / Service / Asynchronous task 
	* Fragments
	* Manifest 
2. Create activity with Intent 
3. Run on emulator/ device
4. Add images to the application
5. Layouts
	* Linear Layout 
	* Relative Layout
6. What is a static variable?
7. Runtime permissions
8. Send n Receive data from servers
	* IP address
	* PHP
	* MySQL
	* Getter / Setter 
9. Debugging 
10. File management 
11. Display data using list view 
12. Garbage collection 

## Android Workshop Pre requisites  

1. Install Android Studio
2. Install LAMP/ WAMP/ MAMP

## Installation Procedure

### Android Studio - IDE

1. The current stable version of android studio can be downloaded from https://developer.android.com/studio/index.html . To download the installer, click on the "DOWNLOAD ANDROID STUDIO" button. 

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/DownloadPage.png">
</p>

2. When prompted, accept the terms and conditions of the installation and then click on the download button.

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/AcceptTnC.png">
</p>

### Android Studio - SDK Setup

1. To setup all android SDK related content, First navigate to the "tools", located on the menu bar at the top of the android studio IDE.

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/Tools.png">
</p>

2. After Expanding the tools, select "SDK Manager" from the drop down list. This will open a dialog which will let you configure your android SDK.

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/toolsExpanded.png">
</p>

3. Make sure that once the android SDK is installed, the necessary platforms checked in the image below are installed on your device.It is not necessary to download all platforms but ensure that you download the platform that corresponds to your mobile phone or the phone you will be using to run the application.

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/SDKManagerPlatforms.png">
</p>

4. To install android SDK or update it, click on the edit button as shown in the picture below to go to the android SDK setup dialog.

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/sdkEdit.png">
</p>

5. Once on the android SDK setup, choose the version of android SDK to download and the location on your device where you want to store the SDK. After this, click on "NEXT" to finsh the android SDK setup. 

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/sdkSetup.png">
</p>

6. After installation of the SDK, navigate back to the SDK manager dialog and select the SDK Tools. On this page, select the tools that are selected in the image below and click on apply/ok to install them. 

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/SDKManagerTools.png">
</p>

### Android Virtual Device (Optional)

1. The android virtual device (or) android emulator is a digital tool that lets you run and test applications without installing them on the mobile device by providing a virtual mobile interface and a virtual operating system that runs on your computer. To setup a virtual device, select the AVD Manager from the "Tools" tab.

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/toolsExpandedAVD.png">
</p>

2. Once on the AVD Manager, Click on the "Create virtual device button"

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/AVDManager.png">
</p>

3. In the virtual device configuration dialog, under category select Phone and then select the hardware profile of your choice. this selection will only affect the size aand resoultion of the AVD interface. After selecting, hit the next button!

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/virtualDeviceConfig.png">
</p>

4. In the system image selection, Download and select any system image that has a release version above Lollipop (api level : 22). and hit next. After this, click finish on the next dialog to finish installation and setup of the AVD. To ensure correct installation of the AVD, launch it from the AVD manager. this should open a new window with the android interface.

<p align="center">
  <img src="https://github.com/initforcode/android-workshop/blob/master/installationProcedure/systemImage.png">
</p>



