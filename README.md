# FrankenPHP Add-On for DDEV

This DDEV add-on for FrankenPHP replaces the currently used webserver
with [FrankenPHP](https://frankenphp.dev/).

FrankenPHP is a modern PHP App Server, written in Go.

Plugin created from https://github.com/ochorocho/ddev-frankenphp

## Installation

```bash
ddev get theodoreb/ddev-frankenphp-drupal && ddev restart
```

## Configuration

[config.yaml](frankenphp%2Fconfig.yaml)

`SERVER_NAME` will be set depending on the VIRTUAL_HOST used by ddev.
This way all domains configured by ddev will be used by frankenphp as well.
