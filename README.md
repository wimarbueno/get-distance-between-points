# distance-between-points
Distance between two points

## Usage
```javascript
var getDistanceBetweenPoints = require('get-distance-between-points');
var distanceInMeters = getDistanceBetweenPoints.getDistanceBetweenPoints(
    -12.119012, -77.029235,
    -12.102870, -77.026983
);

// Outputs: Distance in Meters:  286476.96153465303
console.log("Distance in Meters: ", distanceInMeters);

// Outputs: Distance in Kilometers:  286.476961534653
console.log("Distance in Kilometers: ", (distanceInMeters * 0.001));
```
