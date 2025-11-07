# Final_POE-SWB

The project requires Firebase. So follow the steps given here (Add Firebase to Android Project) to add firebase to your android project.
Download the firebase config file google-services.json
Move the config file to (app) module of the project.
Also, add Cloud Firestore for storing users, products, orders and addresses data. Follow instructions here (Add Cloud Firestore to your app) to add Cloud Firestore to your app.
There need to be two collections - users for Users data and products for Products Data.
This project also, requires OTP based authentication. So, you just need to enable Phone Number sign-in in your firebase project. Follow instructions here (Enable Phone Number sign-in) to enable Phone Number sign-in.
Do not forget to enable app verification for your firebase project. Follow instructions here (Enable app verification) to enable app verification. Add both SHA-1 and SHA-256 fingerprints.
Tried everything but still not able to explore the app due to OTP errors? Don't worry, you can by-pass the OTP screen and explore the app.

Go to app/src/main/java/com/vishalgaur/shoppingapp/Utils.kt file.
Change the return value for function shouldBypassOTPValidation() to true.
You are good to go now. Just run the app and explore.
And take your time to setup the OTP verification. 😉
