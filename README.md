<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/220be08e-1935-4834-b926-548d172143ba">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/e88f79b2-a376-41e3-b9b5-f1b74f010ba7">
  <img height="72pt" alt="Darkly" src="https://github.com/user-attachments/assets/e88f79b2-a376-41e3-b9b5-f1b74f010ba7" />
</picture>
<br>
<br>

![Darkly Firefox](https://github.com/user-attachments/assets/cd9b71ed-c069-4693-94d1-fcf2aa52d3aa)


## Installation
1. Download the files
3. Go to `about:profiles`
2. Find your profile  -  ( *„This is the profile in use and it cannot be deleted.”* )
3. Open the profile's root directory
5. Move the files there
6. Restart Firefox

***

GTK styles have some effect on the appearance of firefox.

This can cause some issues with the colors, the corner radiuses, and the shadows.

For the best experience, I recommend also installing [the darkly gtk theme](https://github.com/wrymt/darkly-gtk)

***

This theme uses `user.js` to load some settings into firefox.

It can only contain settings you can set in `about:config`, and firefox reads it every cold start.

If you see any setting you don't want changed, remove that line before running.

Delete the file once it was applied if you don't want those settings to reset every restart.   

***

https://github.com/user-attachments/assets/8f3003fc-6007-4e43-af9e-636a91b5d4fb

***

### Options supported

`layout.floatingTitlebar` option to use with a floating titlebar


`layout.booooring` option for a more traditional layout 


`layout.accentColorOnTabs` tab highlight on hover with accentcolor


`layout.dynamicTabsize` tabs resize based on the content


**The defaults for all these settings are set by the `user.js` file.**

***

### The good things

Works with many color schemes

High level of detail - more than 1000 thick lines of css

***

### The bad things

Vertical tabs aren't supported yet

Hover and active states sometimes missing

Custom border radius isn't working yet
