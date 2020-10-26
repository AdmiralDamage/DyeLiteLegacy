# Update: Auto mode is working again! you do need to configure something though:
There was another feature hiding in the program that helps us address this, however it was buried. If you enable auto-mode, it wont succeed most of the time due to a change in feature layout. Fortunately the original developer added a ton of contingencies, you have to allow it to find the gauge color again. This is done by intentionally letting the scan fail once, and it should come up with the new color. The new color depends on whether your GUI is transparent, opaque, and what color it itself is so, for now the easiest way to fix the problem yourself is to follow these steps;
1. Enable Auto-mode as usual
2. Prepare the scan as you normally would, and scan for any color, probably pure black as it is the most common.
3. Begin the scan and let it fail and let dyelite click the "Cancel" button.
4. Wait a few seconds and don't interfere with the mouse like you would normally.
5. A garbled dialog box should pop up stating the original gauge color and a new one. (If not, try changing your camera angles or set the gauge color to the default one in the manual I wrote out)

![alt text](https://i.imgur.com/5s0RFUG.png "Confirm Gauge Color Change")

6. Press the "Yes" button after identifying that the Color will change. This automatically changes it, so no need to type anything out.
7. Scan as usual, test with a few scans for black or white. Auto  mode should be working.

I have updated both my user manual and the issue tracker to contain this information in addition to this page. It took a while to figure this out but I hope it helps you and keeps our favourite dye tool going for many more years.
___
### I have made strides towards a new version but a lack of interest in the game says my time is probably much more wisely spent studying and working. I will leave this project up as a repo for the forseeable future - as the name suggests, a legacy version, but features still all mostly work.
___

For those that still wish to download it:

## Do *NOT* use the "*Clone or Download*" button! READ THIS!
Check out the releases, by using the "releases" above, or by going to:
https://github.com/AdmiralDamage/DyeLiteLegacy/releases

## Do read the Issue tracker!
There is a mandatory first step in setting up DyeLite for the Auto mode and some other helpful things to stop noobs, below are links to both.

Mandatory setup:
https://github.com/AdmiralDamage/DyeLiteLegacy/issues/1

Issues/FAQ page:
https://github.com/AdmiralDamage/DyeLiteLegacy/issues
 
### Dyelite is not and never will be a "type in the color, get the perfect dye" program. It is only an aid to the process. It was never designed with giving you a 100% chance of getting your dye, in mind. It's purpose is to simply automate the process as arbitrarily as a computer can.

# DyeLiteLegacy
This repository houses my version of the DyeLite program for Mabinogi.

I saw the issues in DyeLite and decided to attempt a repair myself. I did the best I could with a resource editing program because the source code has been dead and lost since 2009, around 8 years at the time of writing this message, but beyond what is currently done, not much else can be done to save this program. It is for it's original intent and purpose, still 95% functional. This repository will only ever have the most minor fixes done, nothing really functionality wise, probably only the readme or new korean text that I discover.

In the meantime, I am working on a new utility to replace this and others, do not message me about it, it will be out when it is out, if I ever feel like working on it properly.

This is the appearance of the application:


![alt text](http://i.imgur.com/fZJJ3St.png "DyeLite Legacy")


As you can see it is much cleaner than it's older counterpart dubbed the "G12 'English' Version":

![alt text](http://i.imgur.com/ynyzUB2.png "DyeLite G12")
___
Licensing stuff:

The versions of this program produced under my work may not be distributed behind a paywall or adwall. They must only be distributed from this github. It is not allowed for people to collect revenue based on my or the previous authors' work, without them benefitting. It is none of my concern how you pay for your website hosting fees. This is a free tool. You have permission to link to this github and even the release pages. 

Private or personal redistribution (aka sharing between friends over say skype, google drive, etc) is entirely allowed, but only if it is not behind a paywall or adwall such as ad-fly. 

You may not host these files on a public web server such as a forum, link to the release page or this page instead. 
___
If you want to work with me for any reason on this, just shoot me a messsage. You know where you can find me.
