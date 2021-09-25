# Stony Brook University Hacks: ISS-Tracker

## The team: Dario Arias, D'Aundre Doris, and Ifte Ahmed

## Inspiration
Inspired by SpaceX’s Inspiration4 project, our team wanted to track the International Space Station to make it easier for stargazers and space enthusiasts.

Ever wanted to know the current location of the ISS or want to use a telescope to see the station? It's definitely a challenging task due to how fast the ISS is moving (~4.76miles/second). ISS_Tracker will allow you to see the station on an interactive 3-D globe and help you pinpoint when the ISS would arrive at your location if you ever wanted to see it through a telescope. 

## What it does
 Allows the user to view the International Space Station’s position over the Earth in real-time with an interactive 3-D globe. Our application updates the position of the ISS and allows the user to view it on the globe. 

## How we built it
We used Flask, Python,  JavaScript/Html/CSS, Jinja, and Bootstrap for the web application. We also used the ISS API to track the position in real-time. To create the 3-D globe we used amCharts which creates JavaScript charts & maps.

## Challenges we ran into
1. Analyzing the path of the ISS to predict its future location and map when it would arrive over a certain location was the hardest part of the project.
2. Converting standard latitude and longitudes to move to the location of the ISS on our map because the values were different for amCharts. 
3. Map is stuck between new ISS position and whatever point mouse grabs, which happens because of how quickly the ISS updates location (every second almost). 

## Accomplishments that we're proud of
1. Successfully tracking the position of the ISS in real-time and creating a 3-D globe to help display it. 
2. Successfully creating a Map class that allows us to customize our map methods and have more flexibility with what we can do with amCharts. 

## What we learned
We learned Flask and Jinja for this web application.

## What's next for
1. The next steps for our project would be to make our map more interactive and allow the user to view more info about the ISS, such as its current speed and trajectory, etc. 
2. We were struggling to implement the prediction feature which would allow the user to enter an address and it would predict the next time the ISS would be pass by their location.
3. We want to implement a news page on our website, which would allow the user to view info about the station, its passengers, and general space-related news/updates. 

## Check out a mini Demo of our APP below!!!
https://www.loom.com/share/d026b34dbb3842dab77754c131cc98ec

### Links to resources:
- ISS API: http://open-notify.org/Open-Notify-API/ISS-Location-Now/
- amCharts4: https://www.amcharts.com/docs/v4/

- Our Devpost: https://devpost.com/software/iss_tracker
