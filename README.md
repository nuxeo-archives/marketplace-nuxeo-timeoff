# Nuxeo Timeoff

## About

This project allows to build the Marketplace package for the [nuxeo-timeoff](https://github.com/nuxeo/nuxeo-timeoff/) addon.

It depends on the `nuxeo-timeoff` and `nuxeo-cap` marketplace packages.

## Building

To build and run the tests, simply start the Maven build:

    mvn clean install

To run functional tests:

    mvn clean install -Pftest

## Installing

To install the package:

 1. Take a fresh Nuxeo CAP (>= 8.1).

 2. Install the nuxeo-timeoff package:
      - From the AdminCenter (Upload + install)
      - From the command line using `nuxeoctl mp-install marketplace-$VERSION.zip`

