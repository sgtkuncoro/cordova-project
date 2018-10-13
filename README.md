# Example Cordova Project
A simple project to learn cordova

## Android Platform
With external emulator or real device you should have :
* JDK v8/v1.8 or leter
* ADB platform-tools for real device
* Android sdk-tools
* Gradle

## Installation
1. Set enviroment variable JAVA_HOME to java path installation.

    `> set JAVA_HOME=C:\Program Files\Java\jdk1.8.0_162`

2. Set android directory example C:\Android\android-sdk**
    * Extract adb platform-tools and name it "platform-tools" to android installation directory
    * Extract sdk-tools and name it "tools" to android installation directory
    * Install android build-tools by the way in this bellow
    * Open cmd and run the following commands.
    
        `> cd C:\Android\android-sdk\tools\bin`
            
        `> sdkmanager "build-tools;26.0.0"` (for installing android build-tool to android installation directory).

3. Set enviroment variable ANDROID_HOME to path android installation.
    
    `> set ANDROID_HOME=C:\Android\android-sdk`

4. Set enviroment variable to gradle installation directory.

    `> set gradle=C:\gradle-4.5.1\bin`

5. On cordova project
    * To add platform device to cordova project run the following commands.
    
        `> cordova platform add android`
    * To deploy run the following commands.
    
        `> cordova run android `

Referral Link : [https://www.tutorialspoint.com/cordova](https://www.tutorialspoint.com/cordova/)
