# Prime Plow Help

This document provides a summary of the functionality provided by Prime Plow.

* Prime Plow is optimized for Google Chrome
* Last Updated  Tuesday, March 21

* * *
# Login

![Log In](/img/LogIn.png)
* A secure login page requires users to provide a username and password.
* Adding new users to the system is performed by your administrator.
* If you forget your password, use the password reset tool.

* * *

# Map

The map provides four ways to view vehicle information:

* **Live Vehicles**
* **Live Routes**
* **Historic Vehicles**
* **Historic Streets**


After logging in the map will default to the Live Vehicles view. To switch between the map views and access other features of Prime Plow, click on the menu bar in the top left.
![Image: ![Menu Bar Switch](/img/menu-bar-switch03.gif)

## Map Tools & Basic Navigation

The map view is highly interactive. Standard map navigation with mouse and keyboard as well as touch gestures on a tablet are supported.

![Map tools and basic navigation](/img/maptools-basicnav.png)
* **Pan **the map by clicking / tapping and dragging the map.
* **Zoom in / out** on the map by using a mouse scroll wheel or “pinch to zoom”.
* **Click / Tap **on street centerlines to view detailed street information (street name, priority, and last treated time stamp).
* **Address Search Tool: **Enter a street address or intersection to pan / zoom the map.
* **Zoom In / Out & Home:** Click / tap on the home icon to return the map to the original extent.
* **Basemap / Boundary Layers:  **The basemap switcher allows you to change the basemap and turn boundary layers on / off.
* **Street Style Switcher:** This tool is located in the legend and allows you to change they style of the street segments. You may switch between a Priority view and a Simple view.

* * *

## **Live Vehicles**

Live vehicle view provides a real-time view of every vehicle included in your fleet. The live vehicle action panel provides several tools to quickly locate an active vehicle within the map. For snow plows and other vehicles with sensors (sweepers, etc.) the current sensor status is displayed for all live vehicles.


* Selecting a vehicle from the action panel will pan the map and highlight the vehicle.
* The action panel updates in real-time and displays the last message received for the vehicle.
* Vehicles with messages received during the last three (3) hours are highlighted in light blue within the action panel.
* Selecting a vehicle from the map will show a pop-up menu with the last message received for the the vehicle.
* Filtering the list of live vehicles by category will filter the map.
    * i.e. Click Plow to only see plows in the map.
    * i.e. Click Sweeper to only see sweepers in the map.

![Live Vehicles](/img/livevehicles.png)
**Other notes:**

* Vehicle message interval is controlled by Networkfleet configuration. For plows a 15 second reporting interval is strongly recommended. Please contact Networkfleet support to adjust the reporting interval. Also please note faster reporting intervals will increase data fees with Networkfleet.
* Live vehicle breadcrumbs are styled in the map based on their category and whether they are moving or idle.
* Live vehicles that are treating (i.e. plow down, spreader on, brush on) will be highlighted with a yellow circle.

![Other Notes](/img/other-notes.png)* * *

## Historical Vehicles

The historical vehicle view provides tools to search for vehicle breadcrumbs captured over time. There are three basic search filters that can be applied to historical vehicles (**Date**, **Vehicles**, **Location**). You are required to provide a date filter for all historic searches. The results of your search will be shown in a table and within the map. The table and map are interactive, clicking on a record in the table will pan the map and clicking on a breadcrumb from the map will highlight the record in the table. The results table also allows you to sort results on any of the columns (Vehicle, Role, Time, Heading, Speed, Sensor 1, Sensor 2).

**Notes:**

* You can combine filters to find specific breadcrumbs of interest.
* Breadcrumb searches are limited to 10,000 records. If you select a large amount of breadcrumbs you will receive the first 10,000 breadcrumbs that meet your criteria.

###

![Historical Search Date Pickers](/img/historical_search_date_pickers.gif)
**Date Filter:  **The date filter is required for **_all_** historical searches.

* The date filter automatically defaults to the last 12 hours.
* Click or tap the start date and end dates to display the date picker.  
* To adjust the start and times, click on the clock integrated into the date picker.
* You can also type in a date and time using your keyboard.
* Click Fetch to run your search filter.

![Historical Vehicle Filter](/img/historical_vehicle_filter02.gif)
**Vehicle Filter:** The vehicle filter allows you to filter your search for specific vehicles, vehicle groups, or vehicle makes.

* You can use the search box to adjust your filter for a specific vehicle ID (i.e. Plow #10279), Role (i.e. Plow), and or Make (i.e. John Deere).
* To select multiple individual vehicles just separate them with a comma (i.e. 10279.10294).
* Any vehicle with a check-mark will be included in your search results.
* Click Fetch to run your search filter.


![Historical Location Filter](/img/historical_locationfilter_01.gif)

**Location Filter: ** The location filter allows you to search for breadcrumbs within a specific area in the map. You can draw a box on the map, or draw a polygon on the map.

* Click or tap, Box to draw a simple box on the map. To draw on the map, click / tap and drag to create your search box. When you release the click or remove your finger the box will be set.
    * Click Fetch to retrieve vehicles within your search area.
* Click or tap, Polygon to draw a polygon on the map. To draw on the map, click / tap to start the polygon, and continue to click / tap to add vertices to your polygon. To end your polygon double click / tap.
    * Click Fetch to retrieve vehicles within your search area.

* * *

## Live Streets

The live streets view allows you to highlight specific routes and view summary route statistics for each route. This function is **_only _**available during an active snow event. Please view the event management help section for more information on starting and stopping snow events.

![Live Streets](/img/livestreets.png)
* Click on a route from the action panel to pan the map and highlight the segments that belong to the route.
* Review the route statistics (number of passes, percent complete, last treated time stamp.
* You can adjust the street style selection (last visited, was visited, simple streets, etc.) to change how the route highlights impact the map.
* Remember, at any time you can click on an individual street segment to view the last time a street segment was treated.

* * *

## Historic Streets

The historic route view allows you search for treatment activity by route within a given time frame. The form is very similar to historic vehicles, but the information returns individual street segments and their associated treatment information.


**Date Filter:  **The date filter is required for **_all_** historical searches.

* The date filter automatically defaults to the last 12 hours.
* Click or tap the start date and end dates to display the date picker.  
* To adjust the start and times, click on the clock integrated into the date picker.
* You can also type in a date and time using your keyboard.
* Click Fetch to run your search filter.


**Route Filter:** The vehicle filter allows you to filter your search for specific routes.

* Use the search box to adjust your filter for a specific routes(i.e. Route 201, Priority 1, etc.)
* To select multiple routes separate them with a comma (i.e. 201, 202).
* Any route included in your list will be returned by your search (if activity is present).
* Click Fetch to run your search.

![Historical Routes](/img/historical_routes.gif)
**Location Filter: **The location filter allows you to search for route based activity with within a specific area in the map. You can draw a box on the map, or draw a polygon on the map.

* Click or tap, Box to draw a simple box on the map. To draw on the map, click / tap and drag to create your search box. When you release the click or remove your finger the box will be set.
    * Click Fetch to retrieve route treatment within your search area.
* Click or tap, Polygon to draw a polygon on the map. To draw on the map, click / tap to start the polygon, and continue to click / tap to add vertices to your polygon. To end your polygon double click / tap.
    * Click Fetch to retrieve vehicles within your search area.

* * *

# Dashboard

The dashboard provides real-time performance metrics during an active snow event. You can review overall event statistics for previous events, but many of the features are only active during a snow event.

**Event Details:**
The top portion of the dashboard shows key event information (Event Name, Event Start Date, End Date, Duration, Average Temperature, Precipitation).
![Dashboard](/img/dashboard.png)
**Event Statistics:**
This table and chart displays percent complete by priority and a break down of treatment (in miles) over several recent time frames (last hour, 3 hours, and since the beginning of the event).

**Event Trends:**
This chart shows how percent complete has changed over time. This allows you to measure your average cycle time for each priority (i.e. typically three hours of work will result in 50% of priority 1 streets receiving treatment).
![Event Trends](/img/eventtrends.png)
Each line represents a priority, clicking on the line will show the percent complete recorded at that moment in time.

**Current Activity:**
This table displays many vehicles in your fleet have their ignition on and how many routes have a vehicle deployed on them.

**Vehicles By Priority:**
This table shows what priority your vehicles are currently deployed on.
![Vehicles By Priority](/img/vehbypriority.png)
**Last Vehicle Message:**
This is a simple table that updates whenever a new vehicle breadcrumb is received by the system. You can sort the table by each of the columns. The first column (gear) will highlight blue and spin when a recent breadcrumb message is received. Please note this only loads messages received after the dashboard is opened.
![Last Vehicle Message](/img/lastvehiclemessage.png)
**Weather:**
An hourly and daily weather forecast is provided by Dark Sky. You can click on the Powered by Dark Sky link to visit [darksky.com](http://darksky.com/) for more weather details.
![Weather](/img/weather.png)
**Routes:**
This table shows the current number of passes, and the total number of passes performed on each route during the selected snow event.
![Routes](/img/routes.png)* * *

## Events

Event management is a key feature which supports the dashboard metrics. This page is used to start and end snow events and capture snow event updates. Snow events are required to show recent treatment information to the public.

**New Event**
Starting an event will impact the internal map, the internal dashboard, and the public application.

* **Internal map: **After an event is started the internal map view will show street segments based on the last time a plow has treated a street segment.
* **Dashboard: **After an event is started the dashboard will start calculating statistics. The statistics shown are specific to the snow event.
* **Public Site: **After an event is started the “treatment” view displayed in the public application will begin showing treatment information.

![Event Start](/img/Event_Start.gif)

**Event Updates**
Event updates provide a way to document the snow removal process during an active snow event.
![Event Updates](/img/eventupdates.png)
**End Event**
Starting an event will impact the internal map, the internal dashboard, and the public application.

* **Internal map: **Ending an event will clear the map view that shows street segments based on the last time a plow has treated a street segment.
* **Dashboard: **Ending an event will stop the dashboard from calculating statistics.
* **Public Site: **Ending an event will stop the public application from showing the “treatment” view.

* * *

## Vehicles

The vehicle management interface provides a list of all vehicles to be displayed within Prime Plow. Filter tools are available to find a specific vehicle in your fleet.

![Vehicles](/img/vehicles.png)

**Add Vehicle:** Use this tool to add new vehicles to your fleet. Please note your VIN must match the VIN registered with Networkfleet.

**Change Status: **Changing the status will adjust how the vehicle is used within Prime Plow

* **Treating: **Vehicle fully operational and will show treatment and be used for statistics.
* **Not Treating: **Vehicle is operational, but assigned to other work. Any breadcrumbs with the plow down or spreader on will **_NOT _**show treatment or be used for statistics.
* In Maintenance: Vehicle has a mechanical issue or is reporting false data. Any breadcrumbs with the plow down or spreader on will **_NOT _**show treatment or be used for statistics.
* **Unassigned: **Vehicle does not have a status set.
* **Retired: **Vehicle is no longer in use. Vehicle will be hidden / removed from live truck views and historic search filters.


**Delete Vehicle: **Removes a vehicle from your inventory.
* * *

## Messages

The message management page gives your organization control over the messages displayed in the public application.
There are two types of messages to be displayed:

1. **Static Messages: **These messages appear on the right side panel of the public application. These are intended to be used for more permanent messages that provide general information.
2. **Scrolling Messages: **These messages scroll across the public map and are intended to be updated frequently to provide the public with up to date status messages about each snow event.
![Scrolling Messages](/img/scrolling-messages.png)

The following functions are available for both static and scrolling messages:

**Change Message Order: **Click and drag the messages to re-order the messages.

**Edit Message:** Click on the message text to edit the message. Click away from the message and your message is automatically saved.

**Toggle Messages On / Off: **Store common messages and turn them on / off as needed.

**Delete Messages: **Remove messages you don't need.

**Add Messages: **Create a new message from scratch.

**Preview: **Shows a preview of the messages that are turned on.

* * *

## Account

![Account](/img/account.png)

The top right of the menu bar provides an account management tool. The tool allows you to adjust your account settings and logout from the application.

**Account Settings:** The settings page lets you change your name, updated your password, and add / remove user accounts (it  (i.e. name and password. Please note your email address will be your user name when logging into the application. Newly added users will receive an account activation email after being added to the system.

**User Management: **Users can be assigned to several roles. Each role has different functionality within the application.
![User Management](/img/usermanagement.png)

**Logout:** Click here to logout of the application.
* * *
