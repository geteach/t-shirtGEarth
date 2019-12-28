# t-shirtGEarth - Proof of Concept Only 
Google Earth Example file: https://earth.google.com/web/data=Mj8KPQo7CiExNzMzU3VsS2dfekRvMDI0UDBSMEcyUWVKZ1NHN2d4dFASFgoUMEJDQTc5MEQ3QzBCQjk3QzAxNzA

Working on creating new style for Google Earth on Web/mobile.

Goals for this project
1. Create a simplfied css; modifiying Material Design Lite
2. Create higher contrast panel
3. Make sure styling and scripts mostly works on FireFox (WASM).

Issues
1. Custom scrollbar for FF. Maybe one day FF will support more options.
2. Have to run material design lite .js at the end of the page due to error with FF. "Firefox all candidate resources failed to load. media load paused" This causes unstyled white flash the first time css is loaded.
3. Minor spacing issues on smartphones. Maybe will work on this in the future.

The anchor tag ids are created by Google Earth when user creates a place, line, polygon.
The most simple way to get the ids is to create all locations first then export to kml and open in text editor. 
The placemark ids are the internal anchors. **Not sure how stable this is, but all my files have worked for over 6 mths.

Disclaimer...I am a high school teacher who has never taken a coding class, so I am sure there are more effecient ways to create this.

That stated...,
trying to keep it simple in order to teach students and other teachers how to create using custom HTML within Google Earth on Web
