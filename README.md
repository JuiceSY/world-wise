# WorldWise 🌍

WorldWise is an interactive, map-based web application designed to help users document their global travels. Users can pinpoint exact locations they have visited, log dates, and save personal notes about their experiences, creating a visual diary of their worldly adventures.

## 🚀 Features
* **Interactive Map Integration:** Click anywhere on the global map to instantly fetch location data and drop a pin.
* **Travel Logging:** Add custom notes and exact dates to any city you visit.
* **Dynamic Routing:** Seamlessly switch between a list of specific Cities and a broader list of visited Countries.
* **Geolocation:** Automatically find and center the map on your current real-world position.
* **User Authentication:** Secure login gateway for personalized travel tracking.

## 🛠️ Built With
* Vite
* React & React Router
* Leaflet / React-Leaflet (Map Integration)
* CSS Modules / Tailwind CSS
* JSON Server

## 💻 Visual Walk-through

<p align="center">
<b>Landing Page:</b> <br/>
The entry point introducing the app's core mission to track adventures.<br/>
<img src="assets/main_menu.jpg" height="80%" width="80%" alt="WorldWise Landing Page"/>
<br />
<br />
<b>User Authentication:</b> <br/>
Secure login portal for users to access their personal map.<br/>
<img src="assets/login_page.png" height="80%" width="80%" alt="Login Page"/>
<br />
<br />
<b>The Main Dashboard:</b> <br/>
Displays the interactive map with pins of previously visited locations alongside a sortable list of cities.<br/>
<img src="assets/app_page.jpg" height="80%" width="80%" alt="Main Dashboard"/>
<br />
<br />
<b>Adding a New City:</b> <br/>
By clicking on the map, a form dynamically appears allowing the user to log the date and personal notes for that specific location.<br/>
<img src="assets/add_city.jpg" height="80%" width="80%" alt="Add City Form"/>
<br />
<br />
<b>Updating the Tracker:</b> <br/>
Once added, the city immediately populates in the sidebar list and drops a permanent pin on the map.<br/>
<img src="assets/added_city.jpg" height="80%" width="80%" alt="City Added to List"/>
<br />
<br />
<b>Reviewing Travel Notes:</b> <br/>
Selecting a city from the list centers the map on that location and retrieves the user's saved notes and dates.<br/>
<img src="assets/select_city.jpg" height="80%" width="80%" alt="Viewing City Details"/>
<br />
<br />
<b>Country Overview:</b> <br/>
The app automatically parses the city data to generate a consolidated list of all unique countries visited.<br/>
<img src="assets/countries_tab.jpg" height="80%" width="80%" alt="Countries Tab"/>
<br />
<br />
<b>List Management:</b> <br/>
Users can easily manage their logs by deleting cities they no longer wish to track.<br/>
<img src="assets/deleted_city.jpg" height="80%" width="80%" alt="Deleting a City"/>
</p>
