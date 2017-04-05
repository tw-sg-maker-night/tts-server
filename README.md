# Text to Speech Server

* Synthesize text into Speech
* Turn your mac to TTS server with say command. Runs on Mac OS X.
* Only runs on MacOSX. Server that uses the `say` command(Speech Synthesis Manager) in MacOSX
* Created just to use the npm module from [sayserver](https://github.com/tw-sg-maker-night/sayserver.git)

# Server Endpoints
Runs on port 4000

## /speak
* `/speak` is an endpoint that accepts an `HTTP POST` request with two parameters:
  * voice - The Mac OS X voice to speak the text. (optional, default: 'Alex')
  * text - The text to speak. (required)
* Returns a audio file in wav format

# Installations
* `$ npm install`

# To start
* `$ npm start`

# Notes
* Refer to original forked repo for more functionalities
