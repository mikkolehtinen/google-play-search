# google-play-search [![Build Status](https://travis-ci.org/mikkolehtinen/google-play-search.png)](https://travis-ci.org/mikkolehtinen/google-play-search)

> Crawls Google Play store for app details

## Install

Install with [npm](https://npmjs.org/package/google-play-search)

```
npm install google-play-search --save
```

## Example

```js
var googlePlaySearch = require('google-play-search');
googlePlaySearch.fetch('com.google.android.music', function(err, gameData) {
  console.log(gameData);
});
```

## Run tests

```
npm test
```


## License

MIT © [Mikko Lehtinen](http://twitter.com/kosmikko)