# Appium with Gradle and TestNG

Tech tools Used : Gradle, Java, TestNG, Appium server, Appium Inspector, Android SDK, App APK file, ADT, Android Device and Cable.
build.gradle is updated with latest dependancies for all of the above.

To run the test, we need to run the task build.gradle using Gradle.

In this project I have used Payback mobile application to perform a scenario : 
user logs in to the app and navigates to the Coupon Center, filters the coupons by partner (user preferred partner is REWE)
and after that user activate the first enabled Coupon.

Appium server and Inspector have been used to locate the elements for the application.
As an Android device, Have used my personal device to run the test.

For HTML / XML reports, have used TestNG Listeners to provide Test Report.
