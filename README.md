<!--WDI3 2:34 -->
<!--WDI4 1:43 -->
<!--2:30 5 minutes -->
<!--WDI5 9:08 -->

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

<!--WDI5 9:12 -->
<!--2:38 WDI3 -->
<!--2:35 15 minutes -->

## Your first app

The newest version of Ionic allows you to create an app in one line.  Use [this guide](https://ionicframework.com/getting-started/) to get started.

There are two quick ways to run your app.

1. `ionic serve` will open your app in your default web browser
2. `ionic lab` will open your app in your default web browser, but will also allow you to preview the app on an iOS, Android, or Windows device.

Woo hoo, we're coding superheroes!  Now let's dive into the code.

<!--WDI4 1:48 turning over to devs -->
<!--WDI4 coming back 1:55 -->
<!--WDI5 9:20 -->

<!--2:50 WDI3 -->

## App structure

An Ionic app has several folders.  The two most important ones are:

1. The `www` folder, which is similar to the `public` folder of our Node and Express apps.  It is the version of files that actually get loaded on the front end.
2. The `src` folder comprises the files that are compiled and combined to create the files in the `www` folder.  This is where you will do most of the editing in your Ionic app.

Take a couple minutes to familiarize yourself with the files in the `src` folder.  Discuss with a partner your main takeaways from the files, and the code within them.

<!--WDI4 2:00 turning over to devs -->
<!--WDI4 coming back 2:05  -->
<!--2:57 WDI3-->
<!--WDI5 9:33   -->

## Make it your own

Go into the `pages` folder inside `src`, and edit the `Home` template's HTML file to include your name and a basic description of the app you would like to build for Project 4.  No need to change or move any tags, just edit a little text, and save the file.

If you have `ionic lab` or `ionic serve` running, your page will magically refresh every time you save your files.  Cool, right?

<!--3:00 WDI3 -->
<!--WDI4 2:08 turning over to devs -->
<!--WDI4 coming back 2:11  -->
<!--2:50 15 minutes -->

<!--WDI4 turning over to devs 2:13 -->
<!--WDI4 coming back 2:39, 5 minutes to talk about making a new page -->
<!--WDI4 2:54 coming back from break -->
<!--WDI5 9:37  -->
<!--3:05 15 minutes-->

## Testing on your phone

The easiest way to test your live app on your phone is with an app called [`Ionic View`](https://docs.ionic.io/tools/view/), available for iOS and Android.  There are two versions of this app available, one with a white background that just says "Ionic View", and one with a blue background that says "Ionic View - Test & Share Ionic Apps".  Download the one with a blue background onto your phone.

Now go to the [Ionic Dashboard](https://dashboard.ionicjs.com) and Sign Up for a new account (unless you already have one from before).

If you have no other apps, you should be dropped into a "Create a new app" dialog.  If you are not, select the "New App" button in the top-right of the screen and you will go to this "Create a new app" dialog.

Input a name for your new app, and select "Create app".

Follow the directions for "CONNECT EXISTING APP".

When creating your first app, you will also be asked to login.  Enter the same email and password you used to sign up earlier.

Accept all other defaults in this linking process (new SSH key, allowing config changes, etc.).

Once you complete all the steps, if you refresh the page you should see your app code.  Sweet, our code is live!  But Ionic is all about mobile apps.  Let's test this on a phone.

<!--9:47 WDI5 -->

Log in to `Ionic View` on your phone with the same credentials you used to sign up earlier (click the settings tab / gear icon to see the log in screen).  You should now see your fancy new project.  Click on it, and wait a few seconds for it to load.  This is the version of the app your users would see on their phone (assuming they have the same model as you).  Also notice that you can give app feedback in this interface.  Play around with it.  Seems like a real phone app, right?

<!--3:15 WDI4, intro'd builing for iOS, and left open for independent work...getting passwords and usernames stored in Ionic took a while...I think Ionic just takes a while to update-->

<!--3:20 10 minutes -->

## Building for iOS

In order to deploy to an iOS device, you need to go through a [little setup in Xcode](https://ionicframework.com/docs/intro/deploying/).  Once this is done, though, you can open your iOS app that will actually be on the App Store once you get through the App approval process.  Let's see how that happens.

<!-- Instructor demo the non-setup steps like ionic build, and opening on the phone -->

## Building for Android

We don't have enough time to discuss Android in this class, but the process for local testing is similar to that for XCode/iOS.  Your first step is to download [Android Studio](https://developer.android.com/studio/index.html).  See the resources below for more details on deploying.

<!--WDI5 10:17 turning over to devs -->
## Homework

For homework, we would like you to take your initial `tabs` Ionic app and add some of the features we introduced during the Angular week.  Implement the following in your Ionic app:

1. **`Http`**: make an API call to an open API like the [StarWars API](http://swapi.co/).  You can use [this lesson](https://github.com/den-materials/angular/blob/master/lectures/02-routing-apis/star_wars_api.md) as a reference.
2. **Forms**: Add a new model for data that is kept in sync between an HTML form and the Typescript using `[(ngModel)]`.  You can use [this lab](https://github.com/den-materials/angular/blob/master/lectures/01-angular-basics/05-angular-directives.md) as a reference.

## Resources

- [Ionic 2 Crash Course](https://www.youtube.com/watch?v=O2WiI9QrS5s&feature=youtu.be)
- [Deploying to Android or iOS](https://ionicframework.com/docs/v2/setup/deploying/)
- [Ionic 2 Official Tutorial](https://ionicframework.com/docs/v2/setup/tutorial/)
- [Solid Ionic 1 Tutorial](https://ccoenraets.github.io/ionic-tutorial/)
