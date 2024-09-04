# AndromedaOS build 16266 for Production Lumia 950 (Talkman)

# Requirements:
- Production 950 running 14393
- Unlocked bootloader

# Recommended actions after install:
- Provision Windows Device Portal for PC connection
- Install Andromeda Settings and WPDevPortal

# Guide
*Ensure your 950 is on 14393 (untested on higher builds) and is unlocked with Mass Storage access*

*Detailed guide on Release page*

- Boot to flash mode
- Flash FFU with `thor2`
- Unlock bootloader after successful flash (green flash mode)
- Let device boot!
- Connect to Telnet and set Time and Date
- (Optional) Provision Windows Device Portal
- (Optional) Install WPDevPortal and Andromeda Settings
- Enjoy!


### Things to acknowledge:
- Windows Settings app is broken, many incomplete menus and missing settings.
- Many apps that have a minimum target of 16299 will work on this build, you need to modify the AppxManifest to target at least 16266 as minimum build.
- All app packages must have a valid certificate.
- My Andromeda Settings app has an expired certificate, an update is planned to rectify this and add a few more features.
- Volume Keys don't work.


### Personal note:
This build was found November 2023 and was not usable. After spending December and January trying to find workarounds to make the build more user friendly, it was ready to release around 11th January. But due to the original's owners requests was kept private until 26th August 2024 when it was posted on a Discord channel by a different person

This guide was then immediately made public. 

I wont go over the controversy as the story is online if you look. But since then I have been determined to update this build to make it usable as possible, and show off what Andromeda was like around this time!

