# Earthquake Monitor

### Description
The app shows what Earthquakes registered today

On the first screen user can see them on the map

Tapping on the pin provides a litle bit of information, but pressing the Info button on the right opens detail view with full information


Also, user can use tabs to navigate for a list view.

Data don't load from server this time, but from local Database


### Detail page and persistent
When user first click detail the network request happen
If they click next time, the data loading from local Core Data



### Self check

✅ The app contains multiple pages of interface in a navigation controller or tab controller, or a single view controller with a view that shows and hides significant new content.
✅ The user interface includes more than one type of control.


✅ The app includes data from a networked source. 
✅ The networking code is encapsulated in its own classes.
✅ The app clearly indicates network activity, displaying activity indicators and/or progress bars when appropriate.
✅ The app displays an alert view if the network connection fails.


✅ The app has a persistent state that is stored using Core Data or a service with local persistence capabilities (e.g. Firebase or Realm).


✅ The app functions as described in the README, without crashes or other runtime errors.



### Data provider
https://earthquake.usgs.gov/fdsnws/event/1/#parameters

