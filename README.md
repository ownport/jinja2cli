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

