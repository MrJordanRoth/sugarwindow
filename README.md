# SugarWindow

** 12/09/2021 - Due to updates with Sugarmate the JSON connection has been disabled, this will no longer work. **

Displaying your Dexcom readings with Rainmeter (https://www.rainmeter.net/), Dexcom G6 (https://uam1.dexcom.com/), and Sugarmate (https://sugarmate.io/). I found this code on reddit at https://www.reddit.com/r/diabetes/comments/hbxmza/rainmeter_dexcom_sugarmate_desktop_skin/ by a u/turtledave and simply modified it to fit me. I figured I would post it here so other Diabetic or resources could use this as well.

Prerequisites:
1. Must have a login for the Dexcom.
2. Must Sign up for Sugarmate and link your Dexcom data to Sugarmate.3
3. In Sugarmate settings, enable External JSON and take note of the CODE in the URL: http://sugarmate.io/api/v1/**CODE**/latest.json

How to use:
You must open the sugarwindow.ini file and change a few variables to your likeing. You will find those under a section called [Variables] on line 21.
