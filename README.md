# Park-U 

## Installion process for editing code and running App

### Visual Studio Code Setup

__Useful/Recommended Extensions__
- Material Icon Theme
- Prettier
- React Native Tools
- React-Native/React/Redux

__Node Setup and npm Install__
- Go [here](https://nodejs.org/en/download/) to download node for respective OS. Verify npm install via command prompt ``npm -v``
- Open command line, install ``npm install (for Mac, best to use sudo)``
- Next in command line, ``npm i -g expo-cli (for Mac, best to use sudo)``

__Emulator Install__

_I am using android, so I will provide instructions for android, however iOS is very simpe as well_
- Download Android Studio [here](https://developer.android.com/studio/?gclid=CjwKCAjwtfqKBhBoEiwAZuesiDg8_BJqEiZfor_p--qPT_I12LUbijPJtE_dUIHdYNm86KCBMaFpnBoC4hkQAvD_BwE&gclsrc=aw.ds) Standard installion
- Once installion is  complete, you may need to edit bash file, or set path variable. Documenation is [here](https://docs.expo.dev/workflow/android-studio-emulator/)
- Back in Android Studio, select *More Actions, SDK Manager* and here, select a device. (Recent Pixel device is best, with playstore available)
- Finally, select the *play* button to open the phone emulator

## Run the App

- Navigate to folder of react native app via command line
- ``npm start``
- A web browser should open at localhost:19002
- Select ``Run on Android/Device Emulator``

## App should be running now on the Emulator!
