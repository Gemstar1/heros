# heros
Hērōs is a mobile-friendly web application accessible via the Chrome.
# heros 

Heros is a mobile-friendly web application that works by showing Incident Commanders the floorplan to a building layout prior to their team arriving to the scene of an emergency. 

The files in this directory were compiled by Oluwaseun "Seun" Kolawole for Rescunomics LLC.
Contact Sean at bluebridgetechnology@outlook.com or seun@bluebridgetechnology.com

Downloading the .zip of this repository and unpacking will allow you to launch an executable file & install the Heros app on a Windows desktop computer such as the Panasonic Toughbook laptop. 

This software is compatible with the Windows 10 operating system. 

For Android smartphone users on Incident Commander teams, Geolocation must be enabled and "Share my location" must be configured in order to display the user's x, y, z position to the Incident Commander's account from his laptop. 

For demonstration purposes, you can seach for "The Ion" building, view it's address and associated GeoJSON (.geojson file) atop the map's baselayer, and toggle on/off the 45-degree isometric view if the current digital graphic of the building is replaced with the leachandryan/HerosTest repository. 

A fully-functioning alternate version of the originally-scheduled integration can be accessed from https://www.architectingio.com/heros after September 24th, 2022 with the previously-assigned password & user ID emmanuel@rescunomics.com

To use the web application, simply type the address or the name of the building into the search console and press enter to view. 

INDOOR GEOLOCATION TRACKING FEATURE: To access the indoor geolocation tracking feature independently of the UI/UX, go to:
https://leachandryan.github.io/HerosTest (pre-link) or https://rescunomics.github.io/rescutech/heros (post-link).

The indoor geolocation tracking feature was compiled by Architecting I/O's Ryan Leach (@leachandryan on GitHub) to display a smartphone user's Lat Lng Alt (x, y, z) location in the bottom left hand corner of the screen.

Google Maps Developers tools were used to arrive at this solution, which tested accurately to within 1m using the Chrome app on a Google Pixel6a smartphone running the latest version of the Android operating system. Accessing the same link using the Chrome app on an Apple iPhone 12 (iOS operating system) resulted in less accurate x, y, z locations and did not display GeoJSON files, which is why the Google Pixel6a Android smartphone was selected for testing purposes. 

The Ion's building floorplans were converted from PDFs to CAD .dwgs and compressed by eliminating unnecessary labels and graphics. The blueprints were then saved according to the following naming conventions, which spell addresses backwards, taking query speed into account: SS#####StreetName_BuildingName_floor where the first two characters are the code name abbreviation for state and numbers 2 thru 7 in the title's string indicate the 5-digit zip code. 

Using Autodesk AutoCAD and ESRI ArcMap Pro GIS software solutions, Architecting I/O was able to upload the 1:1 scaled vector CAD .dwg plans into the ArcGIS program to georeference the files and preserve their accurate/actual dimensions. The extension pack / extended suite of tools was utilized to project the blueprints atop a basemap in a method that ensured the preservation of metadata (proprietary trade secrets detailed in >75-pages of tutorials in Rescunomics' Notion account. Only through the meticulous reformatting process within ArcGIS could a future-proof file be exported as a lightweight GeoJSON (.geojson file). 

For demonstration purposes, the beginning middle and end files are included in this repository:
TX22002MainStreet4201_TheIon.pdf
TX77002MainStreet4201_TheIon_1.dwg
TX77002MainStreet4201_TheIon_1.geojson

Our web application development process, under the direction of Architecting I/O's scrum master (@ladyluxx on GitHub) conforms to the Scaled Agile Framework® (SAFe®), which is a set of organization and workflow patterns for implementing agile practices at enterprise scale. Our prioritization model of Weighted Shortest Job First (WSJF) enabled us to implement the MVP in order to convince stakeholders our application development project was worth investing in so that the employees and independent contractors working for Rescunomics LLC could scale the application from mere proof-of-concept to county to statewide to nationwide and beyond.

(c) September 22, 2022 RESCUNOMICS LLC. All Rights Reserved. USPTO Patent #
Do not share or distribute without permission. 
Source code property of Rescunomics LLC.
Contact: emmanuel@rescunomics.com
