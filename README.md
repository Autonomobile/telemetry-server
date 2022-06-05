# Telemetry Server

![](https://img.shields.io/badge/license-MIT-blue.svg)
![](https://img.shields.io/badge/status-beta-orange.svg)
![](https://img.shields.io/badge/build-0.5.0-green.svg)

This server helps to collect and analyze telemetry data from autopylot.

![](./public/images/1.png)
![](./public/images/2.png)
![](./public/images/3.png)
![](./public/images/4.png)
![](./public/images/5.png)


## Installation
```bash
npm i

or 

yarn
```

### Start Development
```bash
npm run dev
```
### Start Production build
```bash
npm run build
npm run start
```

then open http://localhost:3000/

## Usage

### Before starting
In your `settings.json` of your autopylot client, change the following line with the host and port you need.
```json
"SERVER_ADDRESS": "ws://localhost:3000"
```

> Don't remove the `ws://` or change the protocol to `http://` as it will not work.


### How to use
- start the server with `npm run start`
- open the client in a browser at http://localhost:3000/ or your custom address
- [start the autopylot client](https://github.com/Autonomobile/AutoPylot#deploy)

> if everything goes well, you should see a popup with a message telling you that a new car is connected.
- select the car with the dropdown menu in the top right corner
- start tracking !

