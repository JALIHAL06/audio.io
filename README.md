   
{
  "name": "mp3-cutter",
  "version": "1.0.6",
  "description": "MP3 Cutter is a JavaScript library and a NodeJS module that allows you to cut your MP3 files by seconds.",
  "keywords": [
    "node",
    "nodejs",
    "mp3",
    "audio",
    "cutter"
  ],
  "author": {
    "name": "Cevad Tokatli",
    "email": "cevadtokatli@hotmail.com",
    "url": "http://cevadtokatli.com"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/cevadtokatli/mp3-cutter"
  },
  "files": [
    "lib",
    "bin"
  ],
  "license": "MIT",
  "bin": {
    "mp3-cutter": "./bin/mp3-cutter"
  },
  "main": "lib/index.js",
  "scripts": {
    "test": "mocha tests/index.js"
  },
  "devDependencies": {
    "chai": "^4.1.2",
    "mocha": "^5.1.1"
  }
}
