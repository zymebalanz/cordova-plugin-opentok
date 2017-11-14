Cordova Plugin for OpenTok iOS and Android
===
##### Disclaimer: This plugin is based on [Cordova OpenTok Plugin](https://github.com/songz/cordova-plugin-opentok/) which has not been actively maintained. Please keep in mind that this is not officially supported by TokBox.

## Sample code 
To see the plugin in action, please check out [opentok-cordova-samples.](https://github.com/msach22/opentok-cordova-samples)

## Using Cordova CLI
Make sure You have Cordova 3.5.0 or greater installed. If you haven't, take a look at the [Cordova instructions](http://cordova.apache.org/docs/en/3.5.0/guide_cli_index.md.html) Page.

Clone this repo to get the source code for the OpenTok Cordova plugin

To install the OpenTok Cordova plugin, run the following command in the root of your project:
```
cordova plugin add https://github.com/msach22/cordova-plugin-opentok/
```  
You can remove the existing OpenTok Cordova plugin by running the following command: 
``` 
cordova plugin remove com.tokbox.cordova.opentok
```

## Getting Started on your Project:
All your editing will be done in your www folder.

To use the opentok library, make sure you include **opentok.js** file in your HTML document.  
` <script type="text/javascript" charset="utf-8" src="opentok.js"></script>`

All JavaScript code should be written in `deviceready` function in */js/index.js* because it is executed after all dependencies has loaded.

    onDeviceReady: function() {
        // Do Your Stuff Here!
    },
    
## Contribute
1. Run `npm install` to install the necessary grunt files  
2. Run `grunt watch` to run grunt tasks automatically after modifying files. This compiles the coffee files to JS and concatenates them  
2. Modify JS components in `src/js/`  
2. Modify iOS components in `src/ios/`  
2. Modify Android components in `src/android/`  
2. Send pull request!  
