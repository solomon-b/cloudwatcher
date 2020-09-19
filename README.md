# cloudwatcher

[![cloudwatcher Build Status](https://travis-ci.org/prikhi/cloudwatcher.svg?branch=master)](https://travis-ci.org/prikhi/cloudwatcher)


A TUI for finding & reviewing 500 errors in AWS cloudwatch.


## Build

You can build the project with stack:

```
stack build
```

For development, you can enable fast builds with file-watching,
documentation-building, & test-running:

```
stack test --haddock --fast --file-watch --pedantic
```

To build & open the documentation, run

```
stack haddock --open cloudwatcher
```


## LICENSE

BSD-3
