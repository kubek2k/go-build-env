# Heroku Buildpack: Go binaries

Buildpack is intended to give a compilation environment for go binaries, which would be further run in Heroku.

## Setup

```
heroku config:set BUILDPACK_URL=https://github.com/kubek2k/go-build-env
```

## Origins

This is a rewrite of a Heroku Go buildpack from @kr: https://github.com/kr/heroku-buildpack-go
