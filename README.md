# Api.ai - webhook implementation in Python

This is a simple webhook implementation that gets Api.ai classification JSON (i.e. a JSON output of Api.ai /query endpoint) and returns a fulfillment response.

# Deploy to:
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# What does the service do?
It's a Bible verse search information fulfillment service that uses [Bible.org API](https://bibles.org/pages/api).

The service packs the result in the Api.ai webhook-compatible response JSON and returns it to Api.ai.

