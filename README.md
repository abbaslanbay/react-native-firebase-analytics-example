
# How to Include Firebase Analytics to your React Native App


A brief description of what this project does and who it's for




![App Screenshot](https://miro.medium.com/max/1400/1*m2UXNCKWbASOCoxpNG9hHA.webp)



You’re building two cellular apps iOS and Android the use of React native. The apps get authorised in their stores. How do you already know if your customers are playing your introduction and discover it beneficial? You don’t except you discover a manner to get insights and understand how your apps are used.

Before integrating Firebase for React local, you need a Firebase task inside the console. This mission will hold statistics for each iOS and Android apps. In my case, I named the assignment firebaseAnalytics.


## Project Create Firebase Console

Enter your project name (example : firebaseAnalytics) and click continue




![App Screenshot](https://miro.medium.com/max/1400/1*Nx0o9e3tCe7P92hraOi37w.webp)

- Select Enable Google Analytics and continue

![App Screenshot](https://miro.medium.com/max/1400/1*LKvWOA9twO3myWiA1NXAKQ.webp)

- Create a new Google Analytics account, select your location and click create project button

![App Screenshot](https://miro.medium.com/max/1400/1*it63-acY76RCOaEXjFkmXg.webp)

- Once you have through the wizard, pick the newly created project.

![App Screenshot](https://miro.medium.com/max/1400/1*rUoaMTsFOxZGPE2tN99uhg.webp)

Now, we want to feature one-of-a-kind apps for specific platforms. For iOS, choose the iOS icon. enter the native challenge’s bundle id (and App store identity, if you have one), provide it a nickname, and press “sign in app.”

![App Screenshot](https://miro.medium.com/max/1400/1*vzmp-AtNlpUBfCXS_eWq9A.webp)

The Firebase console presents a GoogleService-data.plist record. This includes a fixed of credentials for iOS devices to use when authenticating along with your Firebase assignment.

Download the GoogleService-info.plist presented in the second step, and add it to the iOS native project. Don’t overlook to choose the ideal target if you’re having more than one targets. also, don’t forget to choose “copy objects if needed.”

![App Screenshot](https://miro.medium.com/max/1400/1*W-vYKqD2_iH3mm09wISS8w.webp)

Notice: Open GoogleService-data.plist, and permit analytics by way of putting “sure.” The key is IS_ANALYTICS_ENABLED.

![App Screenshot](https://miro.medium.com/max/1400/1*nYFpnoVCUrhD3qwMLAtGLg.webp)


The 1/3 step isn’t relevant for us, as we’re blanketed by the Firebase package deal that’ll upload the pods for us. The fourth step is something we are able to add later. For now, allow’s end with the Firebase console configurations.

The Android side of factors could be very similar. visit the mission homepage, and select the Android icon.


![App Screenshot](https://miro.medium.com/max/1400/1*9lqTRtgKSNhkEeB-Pi6lwA.webp)

![App Screenshot](https://miro.medium.com/max/1400/1*LkPOPqPmjrBhKReAakZ_7w.webp)




## Installation

We’ve got a config file once more — this time known as google-offerings.json. upload it to the local project within the app folder from the Android project folder.

Installation

This module requires that the @react-native-firebase/app module is already setup and installed. To install the “app” module
```bash
npm i @react-native-firebase/app
```
```bash
npm i @react-native-firebase/analytics
```

#### Ios Installation
```bash
cd ios && pod install --repo-update
```

If you get an error like this please update your pod file.




![App Screenshot](https://miro.medium.com/max/1400/1*4dJL3cw49LndTGdCdRw1yA.webp)


![App Screenshot](https://miro.medium.com/max/1400/1*ecmjDDMAomPT9VIISqmXOw.webp)

And that’s quite lots it. What you can do from right here is launch your app and acquire precious facts. Pair it with records from Google Analytics, and you have the energy (and the facts to again it up) to decide what’s the pleasant next flow. 




## Feedback

If you have any feedback, please reach out to us at abbaslanbay@gmail.com

