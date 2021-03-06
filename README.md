# DEVELOP &amp; DEPLOY A FLEET MANAGEMENT DASHBOARD WITH ETISALAT IOT  [3 Nov 2020, 5PM UAE Time]  
Fleet Management is an important IoT use case for smart mobility that coalesces data from various sources and produces a high level analytical view.  

In this session, we’ll build on our introduction (https://www.theassembly.ae/videos/build-a-fleet-management-system-part-i/) last week and show you how to rapidly develop and deploy a rich web dashboard for our system which includes:  
1. Global map and data views for all vehicles 
2. Tabbed views with drill down charts, route/warning history &amp; gauges for individual vehicles 
3. High level analytics with information change history 
4. Admin dispatch commands from the interface app 
5. Geofencing  

We’ll also create a data simulator in the platform to mimic our edge devices and further refine our data inheritance model to accommodate a variety of vehicle types.  

Prerequisites:  No download needed – just activate PTC Cloud free trial (https://developer.thingworx.com/en/resources/trials)

Steps:
1. Activate the PTC Cloud free trial (https://developer.thingworx.com/en/resources/trials) and login to your online instance as Administrator
2. After logging in - import the following entities from the XML objects above
   a. Projects_The Assembly - Fleet Management.xml
   b. Things_VS_AssemblyVehicle.xml 
   c. ThingTemplates_AssemblyVehicle.xml
   d. Things_AssemblyCar1.xml 
   e. Things_AssemblyCar2.xml 
   f. Mashups_AssemblyFleetDashboard.xml 
(These correspond to the diagram and follow on from what we've done in the first session)
