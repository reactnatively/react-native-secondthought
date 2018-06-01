# React Natively

Projects that use React Native to tell the story of humanity. Here we'll capture how humans interact with each other using technology.

## SecondThought
We're creating a simple app to allow iOS &amp; Android users that allows the starting and stopping of audio recording while famous quotes loop in the background.

Users should be able to:
* press record which would begin recording audio to their device
* as well as upload a final audio file to our AWS S3 bucket. 

_PLEASE NOTE: It is important that this app be developed with React Native because we want to deploy to our student group for testing on either iOS or Android devices._

|User Action|View|Priority|
|-|-|-|
|User register|<img src="https://github.com/reactnatively/react-secondthought/blob/master/secondthought-register.png" width="150">|Medium|
|User login|<img src="https://github.com/reactnatively/react-secondthought/blob/master/secondthought-login.png" width="150">|Medium|
|User not recording|<img src="https://github.com/reactnatively/react-secondthought/blob/master/secondthought-home-notrecording.png" width="150">|Critical|
|User currently recording|<img src="https://github.com/reactnatively/react-secondthought/blob/master/secondthought-home-recording.png" width="150">|Critical|

## React Natively API
* URL: http://api.reactnatively.venny.co/v1/
* endpoint: /quotes

|Key|Value (Example)|Description|
|-|-|-|
|token|NWU1MWQ4NzIwOTY0OGNjMTNkZWI1MjNiMjA1ZA==|Token required for access to the API|
|text|If you are not willing to risk the usual you will have to settle for the ordinary.|Quote  (1111 Characters|
|lines|_SVG_|Any SVG paths (1111 Characters)|
|image|directory/subdirectory/image.file|Image file associated with the quote (255 Characters)|
|audio|directory/subdirectory/audio.file|Audio file originated with the quote (255 Characters)|
|longitude|32.7820148|Longitude of user when post occurs|
|latitude|-96.8003555|Latitude of user when post occurs|
|altitude|150|Altitude of user when post occurs|
|author|83838383|User ID of the user authoring object|
|audience|33333333|User ID of the user who is audience to this object|
