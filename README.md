# jinja4cli

The bundle for working Jinja2 templates via command line

## Installation

To make python zip package:

```sh
$ cd jinja4cli
$ zip -r ../jinja4cli.zip .
$ cd ..
$ mv jinja4cli.zip jinja4cli
$ python jinja4cli
Usage: jinja4cli [options] <input template> <input data>

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  --format=FORMAT       format of input variables: auto, ini, json,
                        querystring, yaml, yml
  -e EXTENSIONS, --extension=EXTENSIONS
                        extra jinja2 extensions to load
```

## How to use


```sh
$ python jinja4cli template.j2 params.yaml
```

## Useful links

- [Jinja2: Template Designer Documentation](http://jinja.pocoo.org/docs/dev/templates/) This document describes the syntax and semantics of the template engine and will be most useful as reference to those creating Jinja templates. As the template engine is very flexible, the configuration from the application can be slightly different from the code presented here in terms of delimiters and behavior of undefined values.

