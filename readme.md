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

To install it either download the spotify-api.d.ts file to your repository or **preferably** use tsd:

Obtain tsd from [definitelytyped.org](http://definitelytyped.org/tsd/), install it and run:

```tsd install spotify-api```

Then in your project, reference the file in the top of your ```.ts```:

```/// <reference path="../spotify-api/spotify-api.d.ts" />```


## Tests

To test the package install tsc globally and run this command from the directory of the file: 

```tsc --noImplicitAny spotify-api-tests.d.ts``` 

This verifies that the typings in the ```spotify-api.d.ts``` module match the output from the Spotify API.


## Also check out 

My typings for the ```spotify-web-api-js``` module by JMPerez, coming out shortly also on [DefinitelyTyped.org](http://definitelyTyped.org).

## I hope it's useful to you. Feel free to make pull requests and raise issues.