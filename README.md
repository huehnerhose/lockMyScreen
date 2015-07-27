Switching from Windows to Mac I really missed ```Windows + L``` for quickly lock the screen _without_ going to standby.

After quite a bit of searching I found this line:
```/System/Library/CoreServices/Menu\ Extras/User.menu/Contents/Resources/CGSession -suspend```

I wrapped it via [Thomas Aylott](https://github.com/subtlegradient) appify script and now am able to open Spotlight and type lock.

# Installation & Usage
Simply copy the .app Package to your "Application" folder, open Spotlight and type lock. Hopefully Spotlight learns fast which app you want to use :)
