# go-places
Playing Around with Google Places API and Golang.

## Overview

Goal: Find all "x" locations near "y"

Where x and y are both Places.



---

## TODO:

Define a Place struct

---

## Notes: 

Find Place Request --> Find Place Details
- Two types of requests: `Place Search requests and Place Details requests do not return the same fields.`
- You can use a place search to get a place_id and use that to fetch place details. 

place_id (gathered from a place search)

Nearby search is probably what is needed: https://developers.google.com/maps/documentation/places/web-service/search-nearby

## Google Maps API Key

You'll need an API key specific you Google Maps on your account. Specifically, a billing account with the MAPs API enabled.

