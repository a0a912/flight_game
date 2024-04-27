# Flight Guessing Game

## Context and Backstory
So yeah, my younger brother is a huge fan of aviation. And I mean huge. He de-stresses by going on websites like Flight Radar and memorizing details about flights.

For a Birthday  gift, I want to make him a game he can play on his phone where he guesses a flight's departature city, arrival city and aircraft type. So far, with this prototype version with 1000 flights, he's already crushing it. This man is too good! 😭.

Sadly, I know nothing about flights or aviation so I can't verify how fun the game is from a game design perspective. The most I can do is implement features and make it look nice.

## TODO:

- ~~Make it look like a game~~
- ~~Make the MVP with the basic ability to guess flight info.~~
- ~~Add some basic CSS Styling to highlight correct and incorrect answers~~
- Maybe add a "Aviation Trivia" Screen?
- Maybe make the styling look cooler?

## Current Features and Constraints:
The main point of this game is that I want my younger brother to be able to play this on his iPhone. But apparently, you can't run regular HTML files with JavaScript directly on your phone. You need a specific "HTML viewer" app. This imposes the following constraints:

- The HTML viewer app must be installed on your phone.
- The game must be contained in a single HTML file. I cannot have a seperate JSON file to store the flight data or a seperate CSS stylesheet or a seperate JavaScript file.
- There cannot be any requests or online functionality. This also means everything must be done locally using vanilla HTML, CSS and JavaScript.
