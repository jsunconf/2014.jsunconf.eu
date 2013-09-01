# 2014.jsunconf.eu

The website for the JS Unconf 2014. It is developed with [Wintersmith](http://wintersmith.io).

## Set up

Clone the repo, install wintersmith and the npm modules. Also sass is needed.

```bash
npm install
(sudo) npm install -g wintersmith
gem install sass
```

## Develop

Start the preview server:

```bash
wintersmith preview
```

## Build

To build the static site run:

```bash
wintersmith build
```

Now copy the `build` folder to the server! (Or the correct branch.)