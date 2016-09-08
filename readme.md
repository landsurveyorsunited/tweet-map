#UK Twitter Map

## Installation

- Clone the repo `git clone https://github.com/55sketch/tweet-map.git`
- Install dependencies `npm install`
- Run app `node app`

## Notes

- The Twitter search API, even when requested by location, only returns a small percentage of tweets with geolocation. One possible solution would be to make the function recursive until there are 'X' amount of tweets in the geoTweets array, but performance could be an issue here

## Libraries Used

- [OAuth](https://npmjs.org/package/oauth)
- [Node Twitter](https://github.com/desmondmorris/node-twitter)
- [MapBox](https://www.mapbox.com/mapbox.js/api/v2.4.0)