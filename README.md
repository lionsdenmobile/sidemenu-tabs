# Want to use this?
This is not an Ionic template because it has special code starting at the top 
level (above www) to do a bunch of stuff with hooks, gulp, version numbers, etc.


## Get Started
* Download the latest release and Unzip it somewhere
* Open package.json and change __appId__ and __description__
    * Hold off on the __name__ variable for now

*Note: The package.json variable __name__ should not have spaces in it when you run __npm install__. It will fail.
You can change it after that step.*

## Next Steps
1. Install NPM dependencies found in package.json

    npm install   

1. Look in the package.json and restore the Plugins  listed there.

    ionic state restore --plugins  

1. Add the platform you are working on

    ionic platform add [[android | ios]]

1. Make sure icon and splash screen resources are built

    ionic resources  

1. Test the app on the device

    ionic run   

   *Hooks will make sure App id is changed to DEV before deploying to the device*



TODO:

MORE DOCU

cordova plugin save

Then you can update plugin version if you want, in config.xml and run: cordova prepare