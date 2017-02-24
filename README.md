# hubot-get-servicehubot

Gets the status of a service on the Hubot server

See [`src/get-servicehubot.coffee`](src/get-servicehubot.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-get-servicehubot --save`

Then add **hubot-get-servicehubot** to your `external-scripts.json`:

```json
[
  "hubot-get-servicehubot"
]
```

## Sample Interaction

```
user1>> hubot get service dhcp
hubot>> Service dhcp(DHCP Client) is currently Running.
```
```
user1>> hubot get service wudfsvc
hubot>> Service wudfsvc(Windows Drive Foundation - User-mode Driver Framework) is currently Stopped.
```
## NPM Module

https://www.npmjs.com/package/hubot-get-servicehubot
