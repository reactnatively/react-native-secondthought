# React Natively

Projects that use React Native to tell the story of humanity. Here we'll capture how humans interact with each other using technology.

## SecondThought (Updates)
We're creating a simple app to allow iOS &amp; Android users that allows the starting and stopping of audio recording while famous quotes loop in the background.

|Update needed|Notes|Online resource if available|
|-|-|-|
|User, during onboarding, must be able to choose whether they want to see all quotes or just 1.|Like a playlist||
|User must see a brief tutorial before beginning the core app experience.|Using AsyncStorage we want to ensure users have seen the tutorial screen when opening the app for the first time. Once they have seen it once we'll store this value similar to how we do with login.||
|User must see well-formed date format when reviewing their previously recorded audio.|When displayed the date format should read _Monday the 21st of March at 12:18am (EST)_|https://www.sitepoint.com/whats-the-best-date-format/|
|User must have smooth navigation between audio recording, audio choosing & audio listening.|Use standard headerLeft & headerRight navigation.||https://reactnativecode.com/finish-current-activity-route-screen/|
|User must be able to tell 2 friends about the app.|_/contacts_ endpoint added the Postman collection|https://www.getpostman.com/collections/dbf3d8c70887998389ef|
|User must be able to listen to their previous recordings as a playlist.|||
|User must be 18 years old in order to use the app.|additional _ofAge_ boolean flag sent if "18 years or older text" checked during registration||
|User must be informed their device is recording using an added header bar similar to when Apple Voice Memos is used.|||
|User must be able to open app using Siri or Google.|"Hey Siri, open SecondThought" or "Hey Google, open SecondThought"||
|User device must be able to record 10 minutes without be interrupted by sleep.|||
|User current location must be added to the POST||https://github.com/reactnatively/react-native-uhcounter|
|User must hear "Testing 1, 2, 3" through their device speaker when they begin recording|Audio should play through speaker and not earpiece for both Android and iOS|https://s3.us-east-2.amazonaws.com/reactnatively/testing-1-2-3.mp3|
|User must be able to record audio at the same time as hearing the "Testing 1, 2, 3" prompt|Hopefully, you can record audio while an audio file is playing.|https://docs.expo.io/versions/latest/sdk/audio/|
