# Zipcode Service

This example illustrates the use of Carbon.io to implement a simple
microservice for managing zipcodes.

## Installing the service

We encourage you to clone the git repository so you can play around
with the code. 

```
% git clone git@github.com:carbon-io/example__zipcode-service.git
% cd example__zipcode-service
% npm install
```

## Running the service

To run the service:

```sh
% node lib/ZipcodeService
```

For cmdline help:

```sh
% node lib/ZipcodeService -h
```

## Running the unit tests

This example comes with a simple unit test written in Carbon.io's test framework called TestTube. It is located in the ```test``` directory. 

```
% node test/ZipcodeServiceTest
```

or 

```
% npm test
```

## Generating API documentation (aglio flavor)

```sh
% node lib/ZipcodeService gen-static-docs --flavor aglio --out docs/index.html
```

* [View current documentation](
http://htmlpreview.github.io/?https://raw.githubusercontent.com/carbon-io/example__zipcode-service/master/docs/index.html)
