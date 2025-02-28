# Step-by-Step Guide to Create Your First Project on Android Studio

This guide will help you set up your first Android project using Android Studio on Ubuntu without any errors.

## Prerequisites

- Ubuntu operating system
- Java 11/8/17
- Android Studio
- Internet connection

##  Step 1: Install Android Studio

To install Android Studio on Ubuntu, use the following snap store:

```
sudo snap install android-studio --classic
```

##  Step 2: Open Android Studio
* Launch Android Studio from your applications menu.
* Click on New Project.

##  Step 3: Create a New Project in Android Studio
* Open Android Studio Click on New Project
* Select Empty Views Activity.
* Fill in the following details:
* Name: Apks (the first letter must be uppercase)
* Package name: com.myo.apks
* Language: Java
* Minimum SDK : API 24
* Build Configuration language: Groovy DSL (build.gradle)
* Click Finish

##  Step 4: Update MainActivity.java
* Navigate to [MainActivity.java](https://raw.githubusercontent.com/efxtv/Android-Studio-Android-Hello-World-Project-/refs/heads/main/app/src/main/java/com/myo/apks/MainActivity.java)
* Replace the content with the following code from the provided link: MainActivity.java
* Press CTRL + S to save the file.

##  Step 5: Update AndroidManifest.xml
* Navigate to app > manifests > [AndroidManifest.xml](https://raw.githubusercontent.com/efxtv/Android-Studio-Android-Hello-World-Project-/refs/heads/main/app/src/main/AndroidManifest.xml)
* Replace the content with the following code from the provided link: AndroidManifest.xml
* Press CTRL + S to save the file

##  Step 6: Build the Project
* Click on Build in the menu bar.
* Select Build Bundle(s) / APK(s) and then Build APK(s).
* Locate your APK as shown in the video tutorial.
