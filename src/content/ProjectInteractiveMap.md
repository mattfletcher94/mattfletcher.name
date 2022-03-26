This project was my dissertation at Plymouth University and received
a strong first. Please see the demo <a href="https://youtu.be/Hku3ORswnwE" target="_blank">here</a>.

#### Objectives
The Interactive Holiday Park Map project's main objective was to make the process of 
booking a holiday and exploring a holiday park a more immersive and satisfying
experience. This was accomplished by providing Holiday Park Owners 
with the ability to annotate their Holiday Park maps. Each with its own unique 
configuration, the annotations mark anything from park facilities to camping 
pitches. Holiday Parks that use the Pitched Booking system can integrate it into their 
Interactive Map, linking the system's units with their map annotations. Holiday 
Searchers could then view the Map, click on individual annotations to view more 
information, and search for availability to get a visual representation of which holiday 
pitches or caravans are available on their desired arrival date. For instance, those 
interested in fishing might want to reserve a caravan near the fishing lake.

#### Project Deliverables
The Interactive Holiday Park Map can be broken down into a collection of deliverables, 
each with its own set of tasks and priorities. These deliverables need to be reached 
before the application can be published. Each project has both end-to-end and unit tests.

#### Web Application: Back Office
The first application, referred to as the Back Office, will be for Holiday Park owners to 
create and annotate their interactive maps. It will be set out like an admin dashboard 
and require the user to log in to access it. This application was built using
Vue and BootstrapVue, along with Pixi.js to render the map. 

<a href="https://github.com/mattfletcher94/interactive-map-back-office" target="_blank">See GitHub Repo</a>

#### Web Application: Embedded Map
The second application, referred to as the Embedded Map, will present the interactive 
Map to Holiday searchers. The application can be linked directly or embedded onto 
Holiday Parks' websites and works equally well on desktop and mobile devices.
This application was built using Vue, along with Pixi.js to render the map.

<a href="https://github.com/mattfletcher94/interactive-map-iframe-embed" target="_blank">See GitHub Repo</a>


#### REST API
The REST API, which drives both web applications and follow standard REST 
protocol. Some routes are protected using a JWT authentication mechanism. The 
REST API provides developers with a page of auto-generated documentation.
The REST API was built using Node, Express, TSOA and Mongoose with a MongoDB.

<a href="https://github.com/mattfletcher94/interactive-map-api" target="_blank">See GitHub Repo</a>