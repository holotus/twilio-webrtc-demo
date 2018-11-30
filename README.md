<a href="https://www.twilio.com">
  <img src="https://static0.twilio.com/marketing/bundles/marketing/img/logos/wordmark-red.svg" alt="Twilio" width="250" />
</a>

This demo is built to demo the feature of Twilio WebRTC, and is built on top of the official sample, https://github.com/TwilioDevEd/client-quickstart-js.

## Setting up a local HTTP server

You'll need to load the front end of your web application from a web server for Twilio Client to connect successfully from Chrome (it should work in Firefox if you load it from the file system). The easiest way to do that is to install a local HTTP server like [http-server](https://github.com/indexzero/http-server)

```bash
npm install http-server -g
```

or 

```bash
sudo npm install http-server -g
```

on macOS or Linux


## Run the local server

```bash
http-server
```
