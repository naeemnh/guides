# Introduction

This guide talks about the the resources needed to install and run flutter in your windows system.

# Requirements

Below are the things needed to setup a complete flutter installation in your windows system:
- Flutter
- Android Studio
- Java Development Kit 11

# Installation

## Installing Android Studio

Download the Android Studio from [here](https://developer.android.com/studio) and run the .exe file to start the installation.

### SDK Manager

While in the welcome window of android studio, click the three dots at the top-right corner and select SDK Manager.

Go to Appearance & Behavior -> System Settings -> Android SDK

Under the SDK Platforms tab, select and install the android version that you will be using for development.

Under the SDK Tools tab, select and install the Android SDK Command-line Tools.

## Installing Java Development Kit

Download the JDK11 from [here](https://www.oracle.com/ae/java/technologies/javase/jdk11-archive-downloads.html) i.e. the Oracle website and run the .exe to start the installation.

**Note**: Make sure to have an Oracle account as you will need it to download the file from Oracle website.

Create a variable JAVA_HOME and set it to 'C:\path-to-jdk\jdk11' in your env variables (you will have to restart your PC for the varaible to take effect).

Add the bin folder to the env variable paths i.e. 'C:\path-toj-jdk\jdk11\bin' or '%JAVA_HOME%\bin'

## Installing Flutter

Download the [stable verion](https://storage.googleapis.com/flutter_infra_release/releases/stable/windows/flutter_windows_3.10.0-stable.zip) of flutter and unzip in a reachable folder, example: 'C:\src\flutter'

Add the bin folder 'C:\src\flutter\bin' to the env variables of your windows system.

Finally, follow the instructions from [here](https://docs.flutter.dev/get-started/install/windows#:~:text=dart%20tool%20page.-,Run%20flutter%20doctor,-From%20a%20console) to make sure everything runs smoothly.

