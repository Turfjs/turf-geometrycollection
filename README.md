# turf-geometrycollection

[![build status](https://secure.travis-ci.org/Turfjs/turf-geometrycollection.png)](http://travis-ci.org/Turfjs/turf-geometrycollection)

turf geometrycollection module


### `turf.geometrycollection(coordinates, properties)`

Creates a Feature based on a
coordinate array. Properties can be added optionally.


### Parameters

| parameter     | type                         | description                                                   |
| ------------- | ---------------------------- | ------------------------------------------------------------- |
| `coordinates` | Array\.\<Array\.\<Number\>\> | an array of Positions                                         |
| `properties`  | Object                       | _optional:_ an Object of key-value pairs to add as properties |


### Example

```js
var multiPt = turf.geometrycollection([[0,0],[10,10]]);

//=multiPt
```


**Returns** `Feature.<geometrycollection>`, a geometrycollection feature

## Installation

Requires [nodejs](http://nodejs.org/).

```sh
$ npm install turf-geometrycollection
```

## Tests

```sh
$ npm test
```


