**OpenHAB 1.8.3 scrolling to top fix**

This is a slightly updated version of the web ui that comes bundled with openHAB 1.8.3.

As most who use this may know, the normally bundled version has a bug where upon update of any items, your scroll position is lost and you are returned to the top of the page.

This makes using the web ui next to impossible.

I have updated the javascript file to fix this. I have only tested this on chrome based browsers abut I am guessing this should work fine with firefox as well.

If you wish to have a look at the code changes simply unzip the JAR file above.

To install this simply replace the above JAR file inside your openhab/server/plugins folder. In many linux based distributions this is located in /usr/share/openhab.

I have also made some small changes to the layout / positioning of items to clean things up a little bit.

I am posting this repo as some (like me) are too heavily invested in 1.8.3 to make the upgrade to 2 / 2.5 / 3.0 or newer.

Enjoy!
