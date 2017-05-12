<!--2:30 5 minutes -->

# Intro to Ionic

## Objectives
*By the end of this lesson, developers will be able to:*

- **Describe** the history and use of Ionic
- **Describe** the structure of a typical Ionic app
- **Edit** and **build** an Ionic page
- **Test** an Ionic app with Ionic view

## What is Ionic?

>**From Wikipedia:** Ionic is a complete open-source SDK for hybrid mobile app development. Built on top of **AngularJS** and **Apache Cordova**, Ionic provides tools and services for developing hybrid mobile apps using Web technologies like CSS, HTML5, and Sass. Apps can be built with these Web technologies and then distributed through native app stores to be installed on devices by leveraging Cordova. Ionic was created by Max Lynch, Ben Sperry, and Adam Bradley of Drifty Co. in 2013.

The idea is that one app, generated with HTML, CSS, and JS, can operate on the web, for iOS devices, for Android devices, and more.

<!--2:35 15 minutes -->

## Your first app

The newest version of Ionic allows you to create an app in one line.  Use [this guide](https://ionicframework.com/getting-started/) to get started.

When creating your first app, you will be asked to `Create a free Ionic account`.  This will allow you to test your app on your phone, so type `y` when prompted.  Fill in all the fields in the signup dialog that opens.

Enter a name for your first app.

There are two quick ways to run your app.

1. `ionic serve` will open your app in your default web browser
2. `ionic lab` will open your app in your default web browser, but will also allow you to preview the app on an iOS, Android, or Windows device.

Woo hoo, we're coding superheroes!  Now let's dive into the code.

## App structure

An Ionic app has several folders.  The two most important ones are:

1. The `www` folder, which is similar to the `public` folder of our Node and Express apps.  It is the version of files that actually get loaded on the front end.
2. The `src` folder comprises the files that are compiled and combined to create the files in the `www` folder.  This is where you will do most of the editing in your Ionic app.

Take a couple minutes to familiarize yourself with the files in the `src` folder.  Discuss with a partner your main takeaways from the files, and the code within them.

## Make it your own

Go into the `pages` folder inside `src`, and edit the `Home` template's HTML file to include your name and a basic description of the app you would like to build for Project 4.  No need to change or move any tags, just edit a little text, and save the file.

If you have `ionic lab` or `ionic serve` running, your page will magically refresh.  Cool, right?

<!--2:50 15 minutes -->

## Tutorial

There is another Ionic project type for `tutorial`.  Exit out of your project, go back to your work folder, and follow the steps in [this tutorial](https://ionicframework.com/docs/v2/setup/tutorial/) to get a little more familiar with the Ionic structure and features.  It does not go into much detail, but is a good introduction.  Read all the steps as carefully as possible.

Once you finish the tutorial, put your new lessons into action.  Create a new page called `about` that tells the user all about you.  Make sure this page is accessible from the Ionic Menu, the same way `Hello Ionic` and `My First List` are.

<!--3:05 15 minutes-->

## Testing on your phone

The easiest way to test your live app on your phone is with an app called `Ionic View`, available for iOS and Android.  Download this app on your phone first.

Next, go into the directory of one of your Ionic apps that we created earlier.

Run `ionic upload`.  You will be prompted to log in, using your credentials from earlier in class when you created a free Ionic account.

Log in to `Ionic View` on your phone with the same credentials.  You should now see your fancy new project.  Click on it and select `View App`.  This is the version of the app your users would see on their phone (assuming they have the same model as you).  Also notice that you can give app feedback in this interface.  Play around with it.  Seems like a real phone app, right?

Also, if you want to see your Apps online, you can go to your [Ionic App Dashboard](https://apps.ionic.io/apps/)

<!--3:20 10 minutes -->

## Building for iOS

In order to deploy to an iOS device, you need to go through a [little setup in Xcode](https://ionicframework.com/docs/v2/setup/deploying/).  Once this is done, though, you can open your iOS app that will actually be on the App Store once you get through the App approval process.  Let's see how that happens.

<!-- Instructor demo the non-setup steps like ionic build, and opening on the phone -->

## Building for Android

We don't have enough time to discuss Android in this class, but the process for local testing is similar to that for XCode/iOS.  Your first step is to download [Android Studio](https://developer.android.com/studio/index.html).  See the resources below for more details on deploying.

<!--Once done, intro Angular 2 tutorial -->

## Resources

- [Ionic 2 Crash Course](https://www.youtube.com/watch?v=O2WiI9QrS5s&feature=youtu.be)
- [Deploying to Android or iOS](https://ionicframework.com/docs/v2/setup/deploying/)
- [Ionic 2 Official Tutorial](https://ionicframework.com/docs/v2/setup/tutorial/)
- [Solid Ionic 1 Tutorial](https://ccoenraets.github.io/ionic-tutorial/)
