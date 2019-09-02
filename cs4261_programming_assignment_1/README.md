# CS 4261 Programming Assignment 1

Expense tracker with Firebase database connection and photo-taking functionality.

## Setting up and running the application

The app currently only works on Android. There are some linking and dependency errors with the flutter camera module and iOS that I’m currently unable to resolve. In the future, these issues will be resolved enabling this app to work with both Android and iOS.

To run this app, a few steps are required. Follow the steps at the links below to get the Flutter SDK and Android emulator running:

1.	Flutter SDK: https://flutter.dev/docs/get-started/install/macos#get-the-flutter-sdk
2.	See if Flutter runs correctly: https://flutter.dev/docs/get-started/install/macos#run-flutter-doctor
3.	Update your path: https://flutter.dev/docs/get-started/install/macos#update-your-path
4.	SKIP the iOS setup section!
5.	Set up the Android emulator: https://flutter.dev/docs/get-started/install/macos#set-up-the-android-emulator
  * Device that I used:
    * Name: Pixel 2 API 28 Pie
    * System Image: Pie (this is key!)

Once all of this is done, run the following commands from the repo’s top-level directory (with your emulator on and running):

1.	`cd cs4261_programmingassignment1/cs4261_programming_assignment_1`
2.	`flutter run`

More details on this process can be found at https://flutter-io-deploy-one.firebaseapp.com/getting-started/

Once the code is running, there should be 2 transactions in there that the app pulled from Firebase that I input in there via the app (these are subject to change if I play around with the app more):

1.	Test 1 for $100 on September 2, 2019
2.	Test 2 for $50 on September 1, 2019

