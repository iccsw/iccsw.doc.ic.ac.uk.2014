# iccsw.doc.ic.ac.uk/2014

Powered by [Node.js](http://nodejs.org/) and
[Wintersmith](http://jnordberg.github.com/wintersmith/).

# Getting started

## Installing dependencies

Install NodeJS then run the following in root of the source tree.

```
$ npm install
```
This will read the ``package.json`` file and install the required
dependencies locally into a ``node_modules`` folder.

## Testing

Run the following in the root of the source tree.

```
$ grunt preview
```

This will launch a mini webserver hosting the generated content which you can
use to test your changes. It will automatically regenerate the pages when you
modify files so you don't need to start/stop this when you change source files.

The URL is ``http://localhost:8080/2014/index.html``.

## Deploying

Run the following in the root of the source tree.

```
$ grunt deploy
```
