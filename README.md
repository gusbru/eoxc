# EOxC client framework

[![Build Status](https://travis-ci.org/eoxc/eoxc.svg?branch=master)](https://travis-ci.org/eoxc/eoxc)


## Setup

To install the client framework perform the following steps:

    npm install -g webpack-dev-server webpack
    npm install

## Testing

To run the tests use the following command:

    npm test

To test the example application start the watcher by:

    npm run watch

And navigate the browser to ``path/to/eoxc/test/apps/OpenLayers/index.html``.

TODO: explain dev-server

To run the linter (we use the airbnb style):

    # --silent to suppress the traceback for non-0 exit codes
    npm run lint --silent


## Documentation

To generate the API documentation run:

    npm run docs

