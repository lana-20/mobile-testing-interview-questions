***REPO CONSTRUCTION IS IN PROGRESS***


# <img width=40 src="https://user-images.githubusercontent.com/70295997/222710655-884f2c8e-edab-4c06-9838-5ecba1533ad3.png"> Mobile Testing Q&A

## Most used ADB commands
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-commands).

## List top favorite mobile testing and debugging tools
Review the comprehensive answer in this [repo](https://github.com/lana-20/mobile-testing-debugging-tools).

## I want to capture a video. How can I do it with an adb command?
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-shell-screenrecord/)

## Important Information to Check for in Android Logs → ‘adb logcat’ command, output, filtering	
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-logcat-options-filters).

## Kinds of interruption testing on mobile apps
Review the comprehensive answer in this [repo](https://github.com/lana-20/interruption-interference-testing/).

## If you have several Android devices (virtual emulators and/or physical phones) connected to your machine, how do you install an application?
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-command-redirection).

## If you have an old version installed, and you don’t want to lose your data, how you install a new .apk file?
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-app-reinstall).

## How do you uninstall an application?
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-uninstall-package_name).

## I want to capture a screenshot. How can I do it with an adb command?
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-shell-screencap).

## You started working on your device and you observe a crash. How do you collect logs?
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-logcat-options-filters).

## How do you use <code>adb bugreport</code> command to collect the logs?
Review the comprehensive answer in this [repo](https://github.com/lana-20/adb-bugreport).

## What's an ANR and how does it differ from a Crash?

[ANR vs. Crash](https://github.com/lana-20/anr-vs-crash)

[Crash vs. ANR + ADB logcat vs. bugreport](https://github.com/lana-20/android-crash-anr-logcat-bugreport)

## What is the main difference between <code>adb logcat</code> and <code>adb bugreport</code>?
Review the comprehensive answer in this [repo](https://github.com/lana-20/android-crash-anr-logcat-bugreport).


## Tools used to record crash logs for iOS

There are several tools that can be used to record crash logs for iOS devices. One of the most commonly used tools is Apple's Xcode development environment, which includes a built-in crash log organizer.

- [ ] To use ***Xcode*** to view crash logs for an iOS device, you'll need to connect the device to your computer and select it as the target device in Xcode. Then, go to the "Window" menu and select "Devices and Simulators" to open the Devices window. In the Devices window, select your device, and then select the "Crash Logs" tab to view a list of crash logs for your device.
- [ ] Another tool that can be used to view crash logs for iOS devices is ***iTunes***. To view crash logs using iTunes, connect the device to your computer and select it in iTunes. Then, click the "View Device Logs" button in the "Device" section of the iTunes window.
- [ ] Finally, you can also use the iOS ***Console*** app to view crash logs for an iOS device. To do this, you'll need to install the app from the App Store and then connect the device to your computer using a USB cable. Once the device is connected, the iOS Console app will display a list of crash logs for the device.
- [ ] To access the logs on the physical iOS ***device*** go to *Settings > Privacy > Analytics and Improvements > Analytics Data*.

The retrieved logs may look undecipherable, becauase they are not symbolicated. Devs can [symbolicate](https://betterprogramming.pub/how-to-symbolicate-crash-logs-in-ios-b05637591364) the iOS crash logs before reading them.

## Important things to remember while testing mobile apps

When testing mobile apps, I refer to the [Mobile App Testing Checklist](https://github.com/lana-20/i_sliced_up_fun-SQA-mnemonic#readme).
It's important to consider a variety of factors to ensure a high-quality user experience. This includes testing on a range of devices, operating systems, and network conditions, as well as testing for performance, usability, compatibility, security, accessibility, and localization. Additionally, testing for different user scenarios and flows can help ensure that the app is easy to use and provides a good experience for all users. 

1. Test on a **range of devices**: It's important to test your app on a variety of different devices to ensure that it works well on different screen sizes and hardware/software configurations. This may include testing on different types of phones, tablets, and other mobile devices, as well as testing on different operating systems.
      - [ ] Test for **compatibility**: Make sure that your app is compatible with the different versions of the operating system that it is designed to work on.
      - [ ] Test on **different operating systems**: If your app is available on multiple platforms (e.g. iOS and Android), make sure to test it on all of them to ensure that it functions properly on each platform.
      - [ ] Test for **different screen sizes and resolutions**: Mobile devices come in a wide range of screen sizes and resolutions, so it is important to test your app on devices with different screen sizes to ensure that it looks and functions correctly.

2. Test for **different network conditions**: Mobile devices are often used in a variety of different network conditions, so it is important to test your app under different network conditions (e.g., WiFi, cellular data - 3G, 4G, etc., offline mode) to ensure that it  performs well.

3. Test for **different user flows/scenarios**: Users may use your app in different ways. It is important to test your app for a variety of different user scenarios in order to ensure that it works well in different contexts. For example, you might test your app while the device is in portrait and landscape orientation, while the device is in use by multiple users, or while the device is running low on battery.

4. Test for **accessibility**: Make sure that your app is accessible to users with disabilities, including those who use assistive technologies such as (e.g. screen readers, text-to-speech, etc).

5. Test for **usability**: Make sure that your app is easy for users to navigate and use.

6. Test for **security**: Mobile apps often handle sensitive data (e.g. passwords, personal information, etc.). Make sure that your app is secure and that it protects user data.

7. Test for **performance/stability**: Mobile apps should be fast and stable. Make sure to test your app's performance and stability, including how quickly it loads and how smoothly it runs. Ensure that the app performs well and does not crash or freeze.

8. Test for **localization**: If your app is available in multiple languages, make sure to test it in all of the languages it supports to ensure that the translations are accurate and the app functions properly in each language.

A thorough and systematic approach to testing can help ensure that mobile apps are of high quality and provide a good user experience.

## Difference between mobile and web application testing

When testin mobile apps, I face challenges specific to the mobile market. For example, I have to deal with the memory storage, updates, and more importantly the vast fragmentation of the mobile market. I refer to the [Mobile App Testing Checklist](https://github.com/lana-20/i_sliced_up_fun-SQA-mnemonic#readme) to test mobile-specific crucibles.

1. **Platform**: One of the main differences between mobile and web application testing is the platform on which the app is running. Mobile apps run on specific mobile devices, such as smartphones and tablets, while web apps run on a web browser and can be accessed from any device with an internet connection.
2. **User interface**: Mobile apps often have a different user interface (UI) than web apps, as they are designed to be used on smaller screens with different input methods (e.g., touch screen vs. mouse and keyboard). As a result, testing the Ul of a mobile app may require different approaches than testing the Ul of a web app.
3. **Network conditions**: Mobile apps may be used in a variety of network conditions, including WiFi, cellular data, and offline mode. Testing a mobile app's performance under these different conditions is an important part of the testing process. In contrast, web apps are typically accessed through a stable network via an internet connection, so network conditions are not as significant a factor.
4. **Operating systems**: Mobile devices use a variety of different operating systems, such as Android and iOS, and it's important to test a mobile app on all the operating systems that it will support. Web apps, on the other hand, are accessed via a web browser and are not as affected by the operating system of the device they are being accessed from.
5. **Performance**: Mobile devices have limited processing power and memory compared to desktop computers, so it's important to test the performance of a mobile app to ensure that it runs smoothly on a wide range of devices. Web applications may not have the same performance constraints, although it's still important to test their performance to ensure a good user experience.

## What is mobile fragmentation?

[Detailed Explanation with Supporting Data](https://github.com/lana-20/mobile-fragmentation)

Mobile fragmentation, from the Quality Engineer's perspective, is a challenge of testing a vast variety of devices, screen sizes and resolutions, OSs and OS versions, skins, and UIs. 
A few years ago, Android accounted for about 24,000 distrinct device configurations.
A bug may appear in a particular device-OS configuration, that is not reproducible on other environments. 
For example, I was testing the user registration flow for a biometric authentication app. This flow requires the camera to be pointing at a palm, but in OnePlus 6 device with Android 11 the camera was glitching. So the user was unable to complete the registration.

Definitions (various versions):

_Version 1_

	Mobile fragmentation refers to the diverse range of hardware and software configurations that exist among mobile devices, such as smartphones and tablets. This can include differences in screen size, processor type and speed, amount of memory, and version of the operating system. Mobile fragmentation can make it difficult for developers to create apps that work consistently across all devices, and can also pose challenges for users in terms of accessing certain features or finding compatible apps. In general, the more fragmented a mobile ecosystem is, the more difficult it is for developers to create apps and for users to have a consistent experience across devices.

_Version 2_

	Mobile fragmentation is the term used to describe the wide range of different hardware and software configurations that exist in the mobile device market. This can include differences in the types of processors, screen sizes and resolutions, and operating systems that are used on mobile devices.

	One of the main challenges of mobile fragmentation is that it can make it difficult for developers to create apps and other software that work effectively on all devices. For example, an app that is designed to work on one type of device might not work as well on another device with a different screen size or operating system. As a result, developers may need to create multiple versions of their apps in order to support all the different devices that are available.

	Mobile fragmentation can also be a challenge for users, as it can make it difficult to choose a device that will work well with the apps and services they want to use. Additionally, if an app or service is not available on a particular device, users may need to switch to a different device in order to access it.

_Version 3_

	Mobile fragmentation refers to the wide range of different hardware and software configurations that exist in the mobile market. This includes variations in device brands, models, operating systems, screen sizes, and other hardware and software features. As a result of this fragmentation, it can be difficult for developers to create apps that work seamlessly across all devices and for users to have a consistent experience across different devices.

	One aspect of mobile fragmentation is the diversity of operating systems that are used on mobile devices. While the two most popular mobile operating systems are Android and iOS, there are also many other operating systems used on a smaller scale, such as KaiOS and Tizen. Each operating system has its own set of technical specifications and capabilities, which can make it challenging for developers to create apps that are compatible with all of them.

	Another aspect of mobile fragmentation is the wide range of hardware configurations that exist within each operating system. For example, even within the Android operating system, there are many different device manufacturers, each with their own hardware specifications and capabilities. This can make it difficult for developers to optimize their apps for all of the different hardware configurations that exist.

	Overall, mobile fragmentation can make it challenging for developers to create apps that work consistently across all devices and can lead to a less cohesive user experience for people using different devices.

## How to test a home screen of an app?

![image](https://user-images.githubusercontent.com/70295997/209900744-d06d2390-a5be-4310-971c-97c28e822296.png)
![image](https://user-images.githubusercontent.com/70295997/209900786-fce3924f-f612-42db-9a01-fb3994c1551d.png)
![image](https://user-images.githubusercontent.com/70295997/209900821-c7c6386a-d905-4e0b-94b2-5935a53b4d88.png)
![image](https://user-images.githubusercontent.com/70295997/209900905-8c614798-a702-4805-a8bd-7992dc241141.png)

## What devices to use for mobile testing and how to them set up?

![image](https://user-images.githubusercontent.com/70295997/209901049-b3eedb2f-804e-42a5-9139-5ca3728cb9b9.png)
![image](https://user-images.githubusercontent.com/70295997/209901211-84dc2943-27fa-49c3-a6c5-487e28a20ff9.png)
![image](https://user-images.githubusercontent.com/70295997/209901316-d1a194f4-ce69-4150-a7e9-b35097f6856b.png)
	
## You use the YouTube application, how you can get log file for YouTube?

![image](https://user-images.githubusercontent.com/70295997/209907246-680f03fc-249d-420c-84cd-510fde935b27.png)
![image](https://user-images.githubusercontent.com/70295997/209907319-64e72fec-8e67-4fa2-84d5-4a85c575a154.png)

## You use the Gmail app and you type and a crash happens. How do you justify that crash for this particular app?
	
![image](https://user-images.githubusercontent.com/70295997/209907467-9cbbc155-3953-46fb-a510-8bef09a7639d.png)
![image](https://user-images.githubusercontent.com/70295997/209907558-372c4b29-9387-4f57-92c3-5988be06fa38.png)
![image](https://user-images.githubusercontent.com/70295997/209907614-5e5ac435-291c-471a-ba71-805d2c7f08ef.png)

## If you open your log, what is the information you check for?

## How to install an app on iOS devices?

![image](https://user-images.githubusercontent.com/70295997/209907860-5c6b04a6-c83e-4be1-b187-db3e73e7a304.png)

## How to install an app on iOS devices?

![image](https://user-images.githubusercontent.com/70295997/209908238-d63fe0a6-7a83-4c04-9904-9b4617a6e36d.png)
![image](https://user-images.githubusercontent.com/70295997/209908303-cba56c54-4b52-4098-ba40-5556ac08f324.png)
![image](https://user-images.githubusercontent.com/70295997/209908370-546d572e-4526-480f-a7c5-b3da6ac4a568.png)


To install a test app on an iOS device from your local machine using drag-and-drop, you can use the Xcode integrated development environment (IDE). Here is the general process for installing a test app on an iOS device using Xcode:

Connect the device to your machine: Use a USB cable to connect the device to your machine. Make sure that the device is recognized by Xcode and appears in the Devices window.

Drag and drop the app onto the device: In Finder (on macOS), navigate to the location where the test app is stored. Drag and drop the app onto the device in the Devices window in Xcode.

Wait for the app to install: The app will be installed on the device automatically. You can monitor the progress in the Xcode console.

Test the app: Use the app on the device to test its functionality and behavior. You can use the Xcode debugger to set breakpoints and step through the code, or use other tools and techniques to test the app.

Overall, using Xcode is a simple and straightforward way to install a test app on an iOS device from your local machine using drag-and-drop. This process does not require the use of any command-line tools or commands.

## How to enable Developer Options on Android devices?

To enable Developer Options on an Android device, you can follow these steps:

1. Open the Settings app: From the home screen or app drawer, tap the Settings icon to open the Settings app.
2. Scroll down and tap "About phone": Scroll down to the bottom of the Settings menu and tap the "About phone" option.
3. Tap "Software information": Scroll down to the bottom of the About phone menu and tap the "Software information" option.
4. Tap "Build number" seven times: Tap the "Build number" option seven times. You should see a message that says "You are now a developer!"
5. Go back to the main Settings menu: Tap the back arrow or button to return to the main Settings menu.
6. Enable Developer options: Scroll down to the bottom of the Settings menu and tap the "Developer options" option. Toggle the switch next to "Developer options" to the "On" position.
7. (Optional) Set up USB debugging: In the Developer options menu, toggle the switch next to "USB debugging" to the "On" position. This will allow you to debug your device using a computer and the Android Debug Bridge (ADB) tool.

Overall, enabling Developer options on an Android device is a simple process that allows you to access advanced developer features and settings. Once you have enabled Developer options, you can use them to test and debug your app, as well as customize your device's behavior and appearance.

## How to enable Developer Options on iOS devices?

To enable Developer Options on an iOS device, you can follow these steps:

1. Open the Settings app: From the home screen or app drawer, tap the Settings icon to open the Settings app.
2. Tap "General": Scroll down to the bottom of the Settings menu and tap the "General" option.
3. Tap "Profiles & Device Management": Scroll down to the bottom of the General menu and tap the "Profiles & Device Management" option.
4. Tap your developer account: If you are a registered developer with Apple, you should see your developer account listed under the "Developer App" section. Tap your developer account to open the developer options.
5. Tap "Trust": Tap the "Trust" button to trust your developer account and enable Developer options on your device.
6. Enter your device passcode: Enter your device passcode to confirm the trust operation.
7. (Optional) Set up USB debugging: In the Developer options menu, toggle the switch next to "USB debugging" to the "On" position. This will allow you to debug your device using a computer and the Xcode integrated development environment (IDE).

Overall, enabling Developer options on an iOS device is a simple process that allows you to access advanced developer features and settings. Once you have enabled Developer options, you can use them to test and debug your app, as well as customize your device's behavior and appearance.

## What is Charles Proxy?

Charles Proxy is a popular tool for debugging, testing, and optimizing web and mobile applications. It is particularly useful for mobile testing because it allows you to intercept and inspect HTTP and HTTPS traffic from mobile devices. This can be useful for a wide range of testing and debugging scenarios, such as:

- Verifying that your app is sending and receiving data correctly
- Debugging issues with network requests or responses
- Analyzing the performance of your app's network communication
- Inspecting the data being sent and received by your app
- To use Charles Proxy for mobile testing, you will need to install the Charles Proxy software on your computer and configure your mobile device to use it as a proxy. 

Here is a general outline of the process:

1. Download and install Charles Proxy: Go to the Charles Proxy website and download the latest version of the software. Follow the instructions to install it on your computer.
2. Configure your mobile device: On your mobile device, go to the Wi-Fi settings and tap the name of the Wi-Fi network you are connected to. Scroll down to the "HTTP PROXY" section and tap "Manual". Enter the IP address of your computer and the port number used by Charles Proxy (usually 8888).
3. Start Charles Proxy: On your computer, open Charles Proxy and click the "Start" button to start capturing network traffic.
4. Use your app: On your mobile device, use your app as you normally would. Charles Proxy will capture and display the network traffic generated by your app.
5. Inspect the traffic: In Charles Proxy, you can inspect the traffic captured from your mobile device. You can view the request and response headers, payloads, and other details. You can also use the Charles Proxy tools to analyze and debug the traffic.

Overall, Charles Proxy is a powerful and useful tool for mobile testing that allows you to inspect and debug the network communication of your app. It can be particularly useful for identifying and troubleshooting issues with network requests and responses, and for optimizing the performance of your app.

![image](https://user-images.githubusercontent.com/70295997/209909995-ddd61c6c-f20f-4962-9a5d-60a04f1394c5.png)

## What is Fiddler?

Fiddler is a web debugging tool that allows you to intercept and analyze HTTP traffic between a client (such as a mobile device) and a server. It can be useful for mobile testing in a number of ways:

1. Debugging network requests: Fiddler allows you to view and analyze the network requests made by your mobile app, including the request and response headers, the body of the request and response, and any cookies or other metadata. This can be helpful for debugging issues with network requests, such as errors or timeouts.
2. Modifying network requests: Fiddler allows you to modify the network requests made by your mobile app in real-time. This can be helpful for testing different scenarios, such as different responses from the server or different network conditions.
3. Analyzing performance: Fiddler provides a range of performance metrics, such as the time taken to complete a request and the size of the request and response. This can be helpful for identifying and optimizing the performance of your mobile app.
4. Testing security: Fiddler allows you to intercept and modify SSL/TLS traffic, which can be useful for testing the security of your mobile app.

Overall, Fiddler is a powerful tool for mobile testing that can be used to debug, test, and optimize the network performance of your app. To use Fiddler for mobile testing, you will need to install the Fiddler app on your mobile device and configure your device to use Fiddler as a proxy server. You will also need to install the Fiddler desktop application on your computer and configure it to capture and analyze traffic.

![image](https://user-images.githubusercontent.com/70295997/209910320-4f86c112-268e-4875-bf7e-16b520aa2cca.png)

## What is Appium?

Appium is an open-source tool for automating the testing of mobile applications. It allows you to write and run automated tests for native, hybrid, and web apps on Android and iOS devices. Some of the key features of Appium include:

1. Cross-platform support: Appium supports testing on both Android and iOS platforms, using a single API and a single set of test scripts.
2. Language support: Appium supports a wide range of programming languages, including Java, Python, Ruby, C#, and JavaScript, making it easy to integrate into your existing test automation workflow.
3. Native and web app support: Appium can be used to test native apps (installed on the device) and web apps (accessed through the device's web browser).
4. Inspect and control elements: Appium provides an inspector tool that allows you to inspect the elements of your app and interact with them using test scripts.
5. Integration with other tools: Appium can be integrated with a range of tools and frameworks, such as Jenkins, Selenium, and TestNG, to provide a complete test automation solution.

Overall, Appium is a popular and widely-used tool for automating the testing of mobile applications. It provides a range of features and support for multiple platforms, languages, and app types, making it a flexible and powerful choice for mobile testing.

![image](https://user-images.githubusercontent.com/70295997/209910628-021ee53b-4843-4931-8eb8-87d94b5acd3f.png)

## How to use Appium with Python?

![image](https://user-images.githubusercontent.com/70295997/209910917-948cfed4-6aa7-4182-b116-b6515d1f1460.png)
![image](https://user-images.githubusercontent.com/70295997/209910972-a34cb751-4bab-496d-8d84-ea172b794ddc.png)
![image](https://user-images.githubusercontent.com/70295997/209911074-94c467f8-97f9-4854-8840-1ecca082e3e8.png)











