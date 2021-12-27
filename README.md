# Onlyfans-downloader

Usage-
--------------
install request- python -m pip install requests

First make sure to set your session variables in auth.json first.

./onlyfans-dl.py

Session Variables
Requests to the API now need to be signed. This is an obfuscation technique from the developers to discourage scraping.

You need your browser's user-agent, onlyfans session cookie, x-bc HTTP header, and user-id. Here's how to get them

Get your user-agent here ipchicken
Session Cookie
Login to OnlyFans as normal
Open the dev console Storage Inspector (SHIFT+F9 on FireFox). or the Application tab of Chrome DevTools
Click Cookies -> https://onlyfans.com
Copy the value of the sess cookie
x-bc and user-id
Login to OnlyFans, goto home page
Open dev console F12 -> Network tab (Ctrl+Shift+E in FireFox)
Click Headers sub-tab (default)
Click on one of the JSON elements (may need to refresh page) and look under request headers on the right
There are variables for each of these values at the top of the script. Make sure to update them every time you login or your browser updates.
