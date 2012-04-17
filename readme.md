# CloudFile
Adapted from James Carr's example of nodejs-mongodb-streaming

This application is currently in development, this application will support two interfaces and rely on a central service:

## Web
Users will be able to create accounts on the web service, login, upload files and categorize them, share them with friends

## Mac OS X 
Users will be able to create accounts on the web service, login, upload files and view a link to their web account

## Try it out
### Requirements
* node.js (tested on v0.6.6)
* coffee-script
* mongodb (must be running)
* npmjs

### Running it
Install the dependencies by typing

```bash
  npm install .
```

And run it via coffee by typing

```bash
  coffee app
```
### Running the Tests
From the root of the project:
```bash
  mocha
```