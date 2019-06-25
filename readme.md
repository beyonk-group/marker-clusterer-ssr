<p align="center">
  <img width="186" height="90" src="https://user-images.githubusercontent.com/218949/44782765-377e7c80-ab80-11e8-9dd8-fce0e37c235b.png" alt="Beyonk" />
</p>

## Marker Clusterer SSR

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com) [![CircleCI](https://circleci.com/gh/beyonk-adventures/marker-clusterer-ssr.svg?style=shield)](https://circleci.com/gh/beyonk-adventures/marker-clusterer-ssr) ![ssr-ready](https://img.shields.io/badge/ssr-ready-orange.svg)

### What is it?

This is an ES-ified, linted, bugfixed implementation of the [Google Maps MarkerClusterer](https://github.com/googlemaps/v3-utility-library/tree/master/markerclusterer) component, building on some great, but no-longer-supported [previous efforts](https://www.npmjs.com/package/js-marker-clusterer-universal). It is designed to support SSR and export an ES6 component.

### How do I install it?

#### Via NPM

Simply install the node module into your codebase.

```bash
npm install --save-dev @beyonk/marker-clusterer-ssr
```

and into your code:

```js
import MarkerClusterer from '@beyonk/marker-clusterer-ssr'
```
