# Travel Advisor

Easy to use application that showcases local restraunts, hotels, and attractions for any given location.

## Description

This app was built using React.js and utilzes the Places API, JavaScript API, and RapidAPI's Travel Advisor API. This pulls in hotel, restaraunt, and attractions from any 
given location and uses that data to pinpoit them on a map. This app display various information including location, address, ratings, awards, and links to their websites.

## Getting Started

clone this project locally
run npm/yarn install
run npm start

### Dependencies

Google Cloud Account
RapidAPI account

### Installing

create new project in your [google cloud](https://cloud.google.com/) account
add the Places API & Maps JavaScript API to the project
  
obtain API key for RapidAPI's [Travel Advisor API](https://rapidapi.com/apidojo/api/travel-advisor/)

Inside of the google script tag in public/index.html input your google project's api key where it says <key>
  
create .env file
create env variable named REACT_APP_GOOGLE_MAP_API_KEY and set it equal to your google project's API key
create env variable named REACT_APP_RAPID_API_TRAVEL_API_KEY and set it equal to your RapidAPI key

## Authors

JohnMBarnett

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
