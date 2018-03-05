# Map

The map provides four ways to view vehicle information:
* **Live Vehicles**
* **Live Routes**
* **Historic Vehicles**
* **Historic Streets**

After logging in, the map will default to the Live Vehicles view. To switch between the map views and access other features of Prime Plow, click on the menu bar in the top left.

![Menu Bar Switch](/img/menu-bar-switch03.gif)

## Map Tools & Basic Navigation

The map view is highly interactive. Standard map navigation with mouse and keyboard as well as touch gestures on a tablet are supported.

![Map tools and basic navigation](/img/maptools-basicnav.png)
* **Pan** the map by clicking / tapping and dragging the map.
* **Zoom in / out** on the map by using a mouse scroll wheel or “pinch to zoom”.
* **Click / Tap** on street centerlines to view detailed street information (street name, priority, and last treated time stamp).
* **Address Search Tool:** Enter a street address or intersection to pan / zoom the map.
* **Zoom In / Out & Home:** Click / tap on the home icon to return the map to the original extent.
* **Basemap / Boundary Layers:** The basemap switcher allows you to change the basemap and turn boundary layers on / off.
* **Street Style Switcher:** This tool is located in the legend and allows you to change they style of the street segments. You may switch between a Priority view and a Simple view.

* * *

## **Live Vehicles**

Live Vehicle view provides a real-time view of every vehicle included in your fleet. The Live Vehicle action panel provides several tools to quickly locate an active vehicle within the map. For snow plows and other vehicles with sensors (sweepers, etc.) the current sensor status is displayed for all live vehicles.

* Selecting a vehicle from the action panel will pan the map and highlight the vehicle.
* The action panel updates in real-time and displays the last message received for the vehicle.
* Vehicles with messages received during the last three (3) hours are highlighted in light blue within the action panel.
* Selecting a vehicle from the map will show a pop-up menu with the last message received for the vehicle.
* Filtering the list of live vehicles by category will filter the map.
    * i.e. Click Plow to only see plows in the map.
    * i.e. Click Sweeper to only see sweepers in the map.

![Live Vehicles](/img/livevehicles.png)

> Note: Some features may not have the expected functionality when a snow event is not in progress.

**Other notes:**

* Vehicle message interval is controlled by Networkfleet configuration. For plows a 15 second reporting interval is strongly recommended. Please contact Networkfleet support to adjust the reporting interval. Also please note faster reporting intervals will increase data fees with Networkfleet.
* Live vehicle breadcrumbs are styled in the map based on their category and whether they are moving or idle.
* Live vehicles that are treating (i.e. plow down, spreader on, brush on) will be highlighted with a yellow circle.

![Other Notes](/img/other-notes.png)* * *

## Historical Vehicles

The Historical Vehicle view provides tools to search for vehicle breadcrumbs captured over time. There are three basic search filters that can be applied to historical vehicles (**Date**, **Vehicles**, **Location**). You are required to provide a date filter for all historic searches. The results of your search will be shown in a table and within the map. The table and map are interactive, clicking on a record in the table will pan the map and clicking on a breadcrumb from the map will highlight the record in the table. The results table also allows you to sort results on any of the columns (Vehicle, Role, Time, Heading, Speed, Sensor 1, Sensor 2).

**Notes:**
* You can combine filters to find specific breadcrumbs of interest.
* Breadcrumb searches are limited to 10,000 records. If you select a large amount of breadcrumbs you will receive the first 10,000 breadcrumbs that meet your criteria.

![Historical Search Date Pickers](/img/historical_search_date_pickers.gif)

### Date Filter
The date filter is required for **_all_** historical searches.
* The date filter automatically defaults to the last 12 hours.
* Click or tap the start date and end dates to display the date picker.  
* To adjust the start and times, click on the clock integrated into the date picker.
* You can also type in a date and time using your keyboard.
* Click Fetch to run your search filter.

![Historical Vehicle Filter](/img/historical_vehicle_filter02.gif)

### Vehicle Filter
The vehicle filter allows you to filter your search for specific vehicles, vehicle groups, or vehicle makes.
* You can use the search box to adjust your filter for a specific vehicle ID (i.e. Plow #10279), Role (i.e. Plow), and or Make (i.e. John Deere).
* To select multiple individual vehicles, just separate the criterion with a comma (i.e. 10279, 10294).
* Any vehicle with a check-mark will be included in your search results.
* Click Fetch to run your search filter.

![Historical Location Filter](/img/historical_locationfilter_01.gif)

### Location Filter
The location filter allows you to search for breadcrumbs within a specific area in the map. You can draw a box on the map or draw a polygon on the map using the following options.

* **Box:** Click or tap Box. On the map, click or tap and drag to create your search box. When you release the click or remove your finger, the box will be set. Click Fetch to retrieve vehicles within your search area.
* **Polygon:** Click or tap Polygon. On the map, click or tap to start the polygon, and continue to click / tap to add vertices to your polygon. To end your polygon, double click or tap. Click Fetch to retrieve vehicles within your search area.

Click Fetch to retrieve vehicles within your search area.

* * *

## Live Streets

The Live Streets view allows you to highlight specific routes and view summary route statistics for each route. This function is **_only _** available during an active snow event. Please view the event management help section for more information on starting and stopping snow events.

![Live Streets](/img/livestreets.png)

> Note: Some features may not have the expected functionality when a snow event is not in progress.

* Click on a route from the action panel to pan the map and highlight the segments that belong to the route.
* Review the route statistics (number of passes, percent complete, last treated time stamp.
* You can adjust the street style selection (last visited, was visited, simple streets, etc.) to change how the route highlights impact the map.
* Remember, at any time you can click on an individual street segment to view the last time a street segment was treated.

* * *

## Historic Streets

The Historic Streets view allows you to search for treatment activity by route within a given time frame. The form is very similar to Historic Vehicles, but the information returns individual street segments and their associated treatment information.

### Date Filter
The date filter is required for **_all_** historical searches.
* The date filter automatically defaults to the last 12 hours.
* Click or tap the start date and end dates to display the date picker.  
* To adjust the start and times, click on the clock integrated into the date picker.
* You can also type in a date and time using your keyboard.
* Click Fetch to run your search filter.

### Route Filter
The vehicle filter allows you to filter your search for specific routes.
* Use the search box to adjust your filter for a specific routes(i.e. Route 201, Priority 1, etc.)
* To select multiple routes separate them with a comma (i.e. 201, 202).
* Any route included in your list will be returned by your search (if activity is present).
* Click Fetch to run your search.

![Historical Routes](/img/historical_routes.gif)

### Location Filter
The location filter allows you to search for route based activity with within a specific area in the map. You can draw a box on the map or draw a polygon on the map using the following options.

* **Box:** Click or tap Box. On the map, click or tap and drag to create your search box. When you release the click or remove your finger, the box will be set. Click Fetch to retrieve vehicles within your search area.
* **Polygon:** Click or tap Polygon. On the map, click or tap to start the polygon, and continue to click / tap to add vertices to your polygon. To end your polygon, double click or tap. Click Fetch to retrieve vehicles within your search area.
