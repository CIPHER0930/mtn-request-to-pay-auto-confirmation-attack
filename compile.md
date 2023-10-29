To compile an APK file from all the app sourcecode directories with a Linux OS on your computer, you will need to have the following installed:

Android SDK Platform-tools
Android SDK Build-tools
Java Development Kit (JDK)
Once you have all of the necessary tools installed, you can follow these steps to compile your APK file:

Navigate to the directory where your app sourcecode is located.
Create a new directory called build.
Open a terminal window and navigate to the build directory.
Run the following command to compile your APK file:
gradle assembleRelease
This will compile your app sourcecode and generate an APK file in the build/outputs/apk/release directory.

If you are using a Linux distribution that does not come with Gradle pre-installed, you can install it using the following command:

sudo apt install gradle
Once Gradle is installed, you can follow the steps above to compile your APK file.

Here is an example of how to compile an APK file from all the app sourcecode directories using Linux:

cd my_app
mkdir build
cd build
gradle assembleRelease
This will compile the app sourcecode in the my_app directory and generate an APK file in the build/outputs/apk/release directory.

You can then install the APK file on your Android device using the following command:

adb install build/outputs/apk/release/my_app-release.apk


And with a windows PC :    To compile an APK file from all the app source code directories with a Windows OS on your computer, you can follow these steps:

Install the Android SDK. You can download the Android SDK from the Android developer website.
Install Java 8 or higher. You can download Java from the Oracle website.
Install Gradle. Gradle is a build automation tool that is used to build Android apps. You can download Gradle from the Gradle website.
Create a Gradle wrapper. A Gradle wrapper is a script that allows you to build your Android app without having to install Gradle globally on your system. To create a Gradle wrapper, navigate to your project directory and run the following command:
gradlew init
Open your project in Android Studio. Android Studio is an integrated development environment (IDE) for Android app development. You can download Android Studio from the Android developer website.
Sync your project. To sync your project, click the Sync Project button in the Android Studio toolbar.
Build your APK file. To build your APK file, click the Build button in the Android Studio toolbar.
Find your APK file. Your APK file will be located in the build/outputs/apk/release directory of your project.
Here is an example of how to build an APK file from all the app source code directories with a Windows OS using the command line:

gradlew assembleRelease
This will build your APK file and place it in the build/outputs/apk/release directory of your project.

If you are using a Kotlin project, you will need to use the following command to build your APK file:

gradlew bundleRelease
Once you have built your APK file, you can install it on your Android device or distribute it to your users.
