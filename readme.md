# Typescript Typings for The Spotify Web Api

This repository contains typings for using the Spotify Web Api with Typescript. I aim to make it a complete typing of the API. So far it contains:

* Typings for all object models, both full and simplified, in the [Web API Object Model](https://developer.spotify.com/web-api/object-model/), e.g. Track Object or Album Object,
* Typings for all responses when calling the [Web API Endpoint Reference](https://developer.spotify.com/web-api/endpoint-reference/)

This makes interacting with the Spotify Web API much easier, since you get access to code completion or 'IntelliSense' while coding, and the IDE understands what data you will receive from the API and how to use it.

To be done:

* Integrate the package in existing JS packages for interacting with The Spotify Web API, e.g. [Spotify Web API JS](https://github.com/JMPerez/spotify-web-api-js).
* Complete typings for the option objects for all requests to the API. So far only one is typed the ```SearchForItemParameterObject```.


I hope it's useful to you. Feel free to make pull requests and raise issues.