<div style="width:100%">
<div style="width:100%">
	<div style="width:50%; display:inline-block">
		<p align="center">
		<img align="center" width="180" height="180" alt="" src="https://github.com/cometchat-pro/ios-swift-chat-app/blob/master/Screenshots/CometChat%20Logo.png">	
		</p>	
	</div>	
</div>
</br>
</br>
</div>

CometChat React Native app (built using **CometChat Pro Java Script SDK**) is a text messaging app capable of **one-on-one** (private) and **group** messaging. 

[![Platform](https://img.shields.io/badge/Platform-React--Native-green.svg)](#)      [![Platform](https://img.shields.io/badge/Language-JavaScript-yellowgreen.svg)](#)

## Table of Contents

1. [Config Local Enviroment](#Config-Local-Enviroment)

2. [Config App](#Config-App)

2. [Running the sample app](#Running-the-sample-app)

3. [Contribute](#contribute)


# Config-Local-Enviroment 

Before proceeding, make sure the latest version of Node.js and npm are installed. 

If you are new to React native or do not have react native already setup on your system, please visit the <a href="https://facebook.github.io/react-native/docs/getting-started" target="_blank">React native getting started</a> documentation before configuring app.

## Make CometChat Pro JavaScript SDK Compatible with React Native

We have injected two components from sample app to make Java script SDK compatible with React Native the components are as follows:
1] DOMParser
2] base-64 encode and decode

This is done in LoginScreen.js file in src folder. Here base-64 can be injected globally but DomParser needs to be injected only after CometChat.init().

## Config-App

<h2> v2.0+ </h2>
<h4>
	Git clone and checkout master or v2 branch.
</h4>
<h4>Get your Application Keys</h4>
<a href="https://app.cometchat.io/" target="_blank">Signup for CometChat</a> and then: <br/>
1. Create a new app - select version as v2 and region as Europe or USA. <br/>

  <p>
   <a target="_blank" rel="noopener noreferrer" href="https://github.com/cometchat-pro-samples/react-native-chat-app/chatApp/blob/master/readme screenshots/create-v2-app.gif"><img align="center" src="chatApp/readme screenshots/create-v2-app.gif" style="max-width:100%;"></a>
  </p>

2. Head over to the API Keys section and click on the Create API Key button

3. Enter a name and select the scope as Auth Only

4. Now note the API Key and App ID

5. Replace  `appID`, &nbsp; `apiKey` and &nbsp; `appRegion` in *src/LoginScreen.js* with your APP ID, &nbsp; API KEY &nbsp;and&nbsp; APP Region respectively.<br/>

  <p style="clear:both; display:block;">
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/cometchat-pro-samples/react-native-chat-app/blob/master/readme screenshots/keys.png"><img align="center" src="chatApp/readme screenshots/keys.png" style="max-width:100%;"></a>
  </p>
Note : APP Region values to "us" or "eu".

<h2> v1.0+ </h2>

<h4>
        Git clone and checkout v1 branch.
</h4>

<h4>Get your Application Keys</h4>

  <a href="https://app.cometchat.io/" target="_blank">Signup for CometChat</a> and then:
  <br/>
  1. Create a new app - select version as v1
    
      <a target="_blank" rel="noopener noreferrer" href="https://github.com/cometchat-pro-samples/react-native-chat-app/chatApp/blob/master/readme screenshots/create-v1-app.gif"><img align="center" src="chatApp/readme screenshots/create-v1-app.gif" style="max-width:100%;"></a>
   

  2. Head over to the API Keys section and click on the Create API Key button<br/>

  3. Enter a name and select the scope as Auth Only<br/>

  4. Now note the API Key and App ID<br/>

  5. Replace  `appID` &nbsp; and &nbsp; `apiKey` in *src/LoginScreen.js* with your APP ID, &nbsp;and&nbsp; API KEY respectively.<br/>
  <p style="clear:both; display:block;">
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/cometchat-pro-samples/react-native-chat-app/chatApp/blob/master/readme screenshots/keys.png"><img align="center" src="chatApp/readme screenshots/keys.png" style="max-width:100%;"></a>
  </p>

  <h2> Install dependencies </h2>
    
  ```
  npm install
  ```

  # Running the sample app 

  To run the App in device simulator : 

  <h4><a href="https://facebook.github.io/react-native/docs/running-on-simulator-ios" target="_blank">IOS </a></h4> 

 Using the react-native-cli :
  ```
  react-native run-ios — simulator=”iPhone X”
  ```
  
  <h4><a href="https://facebook.github.io/react-native/docs/running-on-device" target="_blank">Android </a></h4> 

   Using the react-native-cli :
   ```
   react-native run-android
   ```
  ## Contribute
   
   Feel free to make a suggestion by creating a pull request.
   
