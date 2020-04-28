# Testing Webhooks

Webhooks can be enabled in github, such that events in github can trigger a post to the configured webhook.
Github will POST with a payload to the webhook URL.

The webhook URL implements an api to process the POST data.

# Local testing

If you don't have a web service setup, you can implement a temporary internet accessible web service with NGROK.
This proxys an NGROK URL to a service running on your localhost, and then directing it to your webhook service.

The entire flow looks something like this:

github -> webhook -> ngrok server -> ngrok local -> webhook api service -> process POST data

