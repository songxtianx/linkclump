# Linkclump

## Troubleshooting
- Not working? Visit the Linkclump options page (link is found on the Extension page) and make sure you are pressing the correct mouse button and key combination. Please note that chrome automatically disables in-browser extensions on the chrome webstore/extension web pages for security purposes, therefore Linkclump will not work on this page or other pages on this website.
- Problems saving or opening the options page?  Please check you have the latest version of Chrome (at least v23 on windows, v22 on mac/linux) by typing in "chrome://chrome/" in the address bar. The latest version of this extension is using the latest standards and therefore requires the latest version of Chrome. 
- Double tabs? Make sure you don't have a similar extension installed. If you also have "Snap Links Lite" installed it might appear that you are only using Linkclump, but actually these extensions are also working in the background and will try to open tabs also.
- Mandatory key? If you want to use the right mouse button on the Linux/Mac operating systems then you have to select a key. This is due to the way Chrome is designed on these systems and is necessary to make Linkclump work. Left and middle mouse buttons are not affected.
- To use on local pages (i.e. file:// URLs) you need to go to the extensions page (chrome://settings/extensions) and click on the little arrow next to the Linkclump logo. "Allow access to file URLs" option will then appear, which you should tick.
- Does not do what you want it to do? There are a hand full of extension/add ons for different browsers that allow you to open multiple links and therefore there are going to be differences with functionality. I've tried to create this extension so that it is fast and versatile. You are very welcome and encouraged to contribute new features and code improvements to the Linkclump project.
- Known Issues: when zoomed out the scrolling functionality will be jerky

## Todo
- refactor/organize code to make it easier to test (http://ejohn.org/apps/learn/#64)


## Changelog

### v2.7.0
+ Did some basic refactoring and creating SettingsManager

### v2.5.0
+ Open links that only include any/all words

### v2.4.0
+ Allowed home/end buttons to be pressed
+ Added link count
+ Updated files to new chrome standard
+ Fixed interference with spell checker

### v2.3.0
+ Open tabs after current tab
+ Allowed new window to open behind
+ Added close tab time

### v2.2.1
+ Ignore words now works on href and innerHTML

### v2.1.1
+ Fixed scrolling bug issue 
+ Improved scrolling by monitoring mouse out event

### v2.0.17
+ Set "block repeat links in selection" to default to true
+ Allowed floats for the delay

### v2.0.16
+ Delayed mouse up clean up to deal with "bouncing"

### v2.0.11
+ Options page revamped to allow multiple actions
+ Added ability to copy to clipboard and bookmark

### v1.6
+ GUI changes to allow greater option flexibility

### v1.5
+ linkclump box appearing on mouse move on lazy mouse fix

### v1.4
+ fixed background bug
+ removed some jquery code that was too slow

### v1.1.0
+ convert more code to jquery
+ fixed linkclump box wondering
+ improved image dimension finding
+ adding pop-up setup guide on first install
+ improved description

### v1.0.6
+ scroll functionality
+ using jquery 1.4.4 for improved dimensions calculations
+ if link surrounds an image then image dimensions are used
+ moved options to options page
+ improved design

### v1.0.3
+ new window feature added
+ ability to open with shift/alt/ctrl

### v1.0.2
+ exclude words feature added

### v1.0.1
+ smart select added

### v1.0.0
+ allows the user to open multiple links at once
