# Tripmates: JuiCy buNS
Janice Lee  
Cynthia Zhou  
Nancy Luong  
Sophia Kwon

## Description
Tripmates is an online tool to collaboratively plan trips with other people. It provides an organized way for everyone involved in a trip to list activities they’re interested in, as well as an interface to collaboratively construct an itinerary for the trip.

## Notes for Milestone 1: Proof of Concept
Things that aren't quite done yet:
A couple additional checks on details to raise errors in the events api (if someone tries to create an event with an activity that's not in the trip, or with a time range that doesn't fall within the trip dates).
Writing more tests to test situations in which we should expect errors (not logged in, etc).

## Deployed app
http://juicy-buns-tripmates.herokuapp.com/

## Authorship of files:
Sophia Kwon: All files in models, routes, and test, relating to events, itineraries, and trips
Cynthia Zhou: All files in `src/Frontend/itinerary`, `src/Frontend/user`, and parts of other frontend files.

## Installation
`npm i`

## Run locally
`npm run dev` runs both the server and client. Head to `localhost:8080/`

`npm run server` runs only the Express server app on your env's PORT, or port 3000.

`npm run client` runs only the React front-end app on port 8080.

When running both, `webpack.dev.config.js` specifies a proxy that redirects requests from `localhost:8080/api` to `localhost:3000/api`

## Test
`npm test`

