<!--WDI3 2:34 -->
<!--WDI4 1:43 -->
<!--2:30 5 minutes -->
<!--WDI5 9:08 -->
<!--WDI6 1:44 -->

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

1. The newest version of Ionic allows you to create an app in one line.  Use [this guide](https://ionicframework.com/getting-started/) to get started.

2. A question - `Would you like to integrate your new app with Cordova to target native iOS and Android?` -  will pop up in your terminal when you run this command. Reply with `y`.

3. Another question - `Install the free Ionic Pro SDK and connect your app?` -  will pop up in your terminal when you run this command. Reply with `y`.

4. The set up will then ask you for an Email and password.  If you already have an Ionic login, you can enter it here, but if not, you can just enter until the install is finished.  Then run `ionic signup` as the Terminal instructions suggest.

5. This will open a web portal for you to sign up.  Fill in the form.

6. This will lead you to a "Step 2" page.  Select the Kickstarter Plan (free) and then click `Select plan`.

7. Select `Get started with Pro`.

8.  Type in an app name like `first-ionic` and select `Create app`

9. Select `Share app`

10. Select `View Instructions`

11. Select `CONNECT EXISTING APP` under the 2nd instruction (you don't need to run the 1st one, you already did that earlier).

12. Run the commands under the 2nd instruction, in your Terminal.  Use the same `Email` and `Password`.  Select `Automatically setup new a SSH key pair for Ionic Pro`, and type `y` to proceed.

13.  Hit Enter twice to accept a blank passphrase, and type `y` to accept the changes.

14. Run the following commands:

  a. `git add -A`
  b. `git commit -m "Pushing to Ionic"`
  c. `git push ionic master`

## Opening Your App

There are two quick ways to run your app.

1. `ionic serve` will open your app in your default web browser
2. `ionic lab` will open your app in your default web browser, but will also allow you to preview the app on an iOS, Android, or Windows device.

Woo hoo, we're coding superheroes!  Now let's dive into the code.

<!--WDI6 coming back 2:15  -->
<!--WDI4 1:48 turning over to devs -->
<!--WDI4 coming back 1:55 -->
<!--WDI5 9:20 -->

<!--2:50 WDI3 -->

## App structure

An Ionic app has several folders.  The two most important ones are:

1. The `www` folder, which is similar to the `public` folder of our Node and Express apps, or the `dist` folder of our Angular apps.  It is the version of files that actually get loaded on the front end.
2. The `src` folder comprises the files that are compiled and combined to create the files in the `www` folder.  This is where you will do most of the editing in your Ionic app.

Take a couple minutes to familiarize yourself with the files in the `src` folder.  Discuss with a partner your main takeaways from the files, and the code within them.

<!--WDI4 2:00 turning over to devs -->
<!--WDI4 coming back 2:05  -->
<!--2:57 WDI3-->
<!--WDI5 9:33   -->
<!--WDI6 coming back 2:26 -->

## Make it your own

Go into the `pages` folder inside `src`, and edit the `Home` template's HTML file to include your name and a basic description of the app you would like to build for Project 4.  No need to change or move any tags, just edit a little text, and save the file.

If you have `ionic lab` or `ionic serve` running, your page will magically refresh every time you save your files.  Cool, right?

<!--3:00 WDI3 -->
<!--WDI4 2:08 turning over to devs -->
<!--WDI4 coming back 2:11  -->
<!--2:50 15 minutes -->
<!--WDi6 2:3  -->

<!--WDI4 turning over to devs 2:13 -->
<!--WDI4 coming back 2:39, 5 minutes to talk about making a new page -->
<!--WDI4 2:54 coming back from break -->
<!--WDI5 9:37  -->
<!--3:05 15 minutes-->

## Testing on your phone

The easiest way to test your live app on your phone is with an app called [`Ionic View`](https://docs.ionic.io/tools/view/), available for iOS and Android.  There are two versions of this app available, one with a white background that just says "Ionic View", and one with a blue background that says "Ionic View - Test & Share Ionic Apps".  Download the one with a blue background onto your phone.

Now go back to the [Ionic Dashboard](https://dashboard.ionicjs.com) page for your app.  Refresh the page.

Click the Deploy button on the right hand side of the bar for `Pushing to Ionic`.

Sweet, our code is live!  But Ionic is all about mobile apps.  Let's test this on a phone.

<!--9:47 WDI5 -->

Log in to `Ionic View` on your phone with the same credentials you used to sign up earlier (click the settings tab / gear icon to see the log in screen).  You should now see your fancy new project.  Click on it, and wait a few seconds for it to load.  This is the version of the app your users would see on their phone (assuming they have the same model as you).  Also notice that you can give app feedback in this interface.  Play around with it.  Seems like a real phone app, right?

<!--3:15 WDI4, intro'd builing for iOS, and left open for independent work...getting passwords and usernames stored in Ionic took a while...I think Ionic just takes a while to update-->

<!--WDI6 2:43  -->
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

<!--3:00 WDI6 -->

## Resources

- [Ionic 2 Crash Course](https://www.youtube.com/watch?v=O2WiI9QrS5s&feature=youtu.be)
- [Deploying to Android or iOS](https://ionicframework.com/docs/v2/setup/deploying/)
- [Ionic 2 Official Tutorial](https://ionicframework.com/docs/v2/setup/tutorial/)
- [Solid Ionic 1 Tutorial](https://ccoenraets.github.io/ionic-tutorial/)
