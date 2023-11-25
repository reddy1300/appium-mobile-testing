### Appium-Basics

- Appium is open-source Mobile automation tool for testing Apps (Android and IOS) and mobile browsers.
- Appium literally uses WebDriver Json wire (Which Selenium does) to test the Apps. so it is just like selenium.

### Syllabus
- Appium's installation on Windows and MAC
- Android Automation testing with appium on virtual devices and real devices
- IOS automation testing with appium on virtual devices and real devices
- Hybrid app's automation with appium
- Mobile browser automation with appium
- Database testing with appium
- Appium Hybrid framework design from scratch.
- Appium cloud execution wu=ith parallel run capabilities.

**APPIUM:**
- Open source mobile automation tool.
- The only cross-platform test supporting tool.
- Works for native, hybrid, and mobile web apps.
- Supports Web Driver API - selenium family.
- **native:** If app is exclusively developed on Android or IOS then it called native.
- **hybrid:** some apps designed to involve mobile platform as well as web platform 

**Supported:**
- IOS
- Android
- Firefox OS

**Languages:** Java, C#, JS, Python, Ruby

**Appium Architecture**

 ![Appium Architecture](/src/Images/Appium-Architecture.jpg)
 
- Testing frameworks provided in underhood by Android (UIAutomator2), IOS (XCUITest)

**Step-by-Step Instructions for Appium Configuration in Windows / MAC:**

- Install Java and set path in system environment variables.
- Install Android Studio and find out the Android SDK path and set in system environment variables.
- Install Node (Because Appium Server totally build on Node.js)
- To set environment variables in MAC `vi ~/.bash_profile`
- `export JAVA_HOME=$(/usr/libexec/java_home)`
- `export ANDROID_HOME=/users/rahulshetty/Library/Android/sdk`
- `export PATH=$PATH:$ANDROID_HOME/platform-tools`
- `export PATH=$PATH:$ANDROID_HOME/tools/bin`
- `source ~/.bash_profile` we have to store otherwise we will last this setup.
- In MAC by separating with : we can set multiple paths in single line.
- To see path set for different variables `echo $Java_HOME`
- TO see all paths `echo $PATH`
- Open Android Studio and Configure Emulator/Virtual Device.
- Install and start the appium server via Node.
- `npm install -g appium`

**UIAutomator2:**
- UI Automator is a UI testing framework introduced by Google to facilitate automation on a android device or emulator.
- Appium leverages this UIAutomator with its own wrapper and came up with UIAutomator2 Driver to automate the Android Apps.
- By default, appium drivers not come up with appium, so we have to install drivers separately.
- To see available & installed appium drivers list ` appium driver list`
- To install driver `appium driver install uiautomator2`

