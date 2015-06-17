Switching from Windows to Mac I really missed ```Windows + L``` for quickly lock the screen _without_ going to standby.

After quite a bit of searching I found this line:
```/System/Library/CoreServices/Menu\ Extras/User.menu/Contents/Resources/CGSession -suspend```

I wrapped it via [Thomas Aylott](https://github.com/subtlegradient) appify script and now am able to open Spotlight and type lock.

# Installation & Usage
Simply copy the .app Package to your "Application" folder, open Spotlight and type lock. Hopefully Spotlight learns fast which app you want to use :)

# Uncertanties
On my quest of getting that simple locking mechanism, I had a pitstop at the solution of creating a second user account, getting my logged in user shown in the menu bar and clicking on "switch user". I am not 100% certain if this script works without a second user on your system. It would be wonderful, if anyone could test it and give me feedback.
