# Missing Required Icon File

In a project with Xamarin Forms, when compiling the iOS application and trying to upload it to the store I got an error.  I had this problem when I uploaded the app through Xcode.

The mistake was that I was missing some images that I did have in my project and I can see. Like, the app store icon or the application icon you don't have.

I fixed it as follows, 


## Move the icon into the resources from the folder into the Assets.xcassets

![alt text](https://github.com/jorgemht/MissingRequiredIconFile/blob/master/AppIcon%20in%20resources.PNG
)


## Delete the AppIcon from .xcassets

![Delete the AppIcon from xAssets](https://github.com/jorgemht/MissingRequiredIconFile/blob/master/AppIcon.PNG)


## Update my info.plist

![alt text](https://github.com/jorgemht/MissingRequiredIconFile/blob/master/AppIcon%20in%20resources%20info%20plist.PNG)


For some strange reason even app icons gave me errors, so I moved them to resources .... and fixed. 
