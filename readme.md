# Typescript Typings for The Spotify Web Api

This repository contains typings for using the Spotify Web Api for use with Typescript. 

It contains:

* Typings for all object models, both full and simplified, in the [Web API Object Model](https://developer.spotify.com/web-api/object-model/), e.g. Track Object or Album Object,
* Typings for all responses when calling the [Web API Endpoint Reference](https://developer.spotify.com/web-api/endpoint-reference/)
* Tests of the typings for all API endpoint responses.

This makes interacting with the Spotify Web API much easier, since you get access to code completion or 'IntelliSense' while coding, and the IDE understands what data you will receive from the API. You get all the advantages of static typing.

Still to be done:
* Complete typings for the option objects for all requests to the API. So far only one is typed the ```SearchForItemParameterObject```.

## Usage

Get the package with ```npm install @types/spotify-api``` or use obtain tsd from [definitelytyped.org](http://definitelytyped.org/tsd/), install it and run ```tsd install spotify-api``` from the root of your site.

Alternatively, download ```index.d.ts``` from this repo.

Then in your project, reference the file in the top of your ```.ts```:

```/// <reference path="../node_modules/@types/spotify-api/spotify-api.d.ts" />```

(or what the path to the file is from your project...)

## Tests

To test the package install tsc globally and run ```tsc``` in this directory.

This verifies that the typings in the ```spotify-api.d.ts``` module match the output from the Spotify API.


## Also check out 

My typings for the [spotify-web-api-js](https://github.com/JMPerez/spotify-web-api-js) package by JMPerez, which is integrated in the package.

## I hope it's useful to you. Feel free to make pull requests and raise issues.