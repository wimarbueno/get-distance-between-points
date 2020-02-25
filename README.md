# get-distance-between-points
Distance between two points of coordinates in Google Maps - Earth

[![Build Status](https://travis-ci.org/wimarbueno/get-distance-between-points.svg?branch=master)](https://travis-ci.org/wimarbueno/get-distance-between-points)

## Installation
```sh
$ npm install get-distance-between-points --save
```

## Usage
```javascript
var getDistanceBetweenPoints = require('get-distance-between-points');
var distanceInMeters = getDistanceBetweenPoints.getDistanceBetweenPoints(
    -12.119012, -77.029235, // Lat, Long of point A
    -12.102870, -77.026983 // Lat, Long of point B
);

// Outputs: Distance in Meters:  1813.5586276614192
console.log("Distance in Meters: ", distanceInMeters);

// Outputs: Distance in Kilometers:  1.8135586276614193
console.log("Distance in Kilometers: ", (distanceInMeters * 0.001));
```
