# Minimal MQTT + WebSockets broker

Minimal MQTT broker with WebSockets interface

## Setup

Requirements:

- npm
- MongoDB

After cloning, run:

```sh
# Install dependencies
npm install
# Start the MongoDB daemon
mongod
# Start the actual server
node .
```

By default, the MQTT broker will be available through the port 1883 and its WebSockets interface through the port 9000 (the latter is defined in `index.js`).
