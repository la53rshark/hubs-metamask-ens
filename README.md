# Mozilla Hubs Metamask+ENS Integration
THIS REPO IS FOR DEMONSTRATION PURPOSES AT THE MOMENT AND SHOULD NOT BE USED IN ANY PRODUCTION CAPACITY. 

> If this repo helped you, feel free to send coin or wares to `la53rshark.eth` as a thank you.

[![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)

The client-side code for [Mozilla Hubs](https://hubs.mozilla.com/), an online 3D collaboration platform that works for desktop, mobile, and VR platforms modified to connect with metamask and ens.

## Getting Started

If you would like to run Hubs on your own servers, check out [Hubs Cloud](https://hubs.mozilla.com/docs/hubs-cloud-intro.html).

If you would like to deploy a custom client to your existing Hubs Cloud instance please refer to [this guide](https://hubs.mozilla.com/docs/hubs-cloud-custom-clients.html).

If you would like to contribute to the main fork of the Hubs client please see the [contributor guide](./CONTRIBUTING.md).

If you just want to check out how Hubs works and make your own modifications continue on to our Quick Start Guide.

### Quick Start

[Install NodeJS](https://nodejs.org) if you haven't already. We recommend version 12 or above.

Run the following commands:

```bash
git clone git@github.com:la53rshark/hubs-metamask-ens.git
cd hubs
npm ci
npm run dev
```
make a file called `.env` that contains the following env vars.
```
host=hubs.local
HOST_IP=hubs.local
```

If you want to deploy, run the following

```
npm run login
```

Follow the instructions for your Hubs Cloud instance details.

```
npm run deploy
```


## Documentation

The Hubs documentation can be found [here](https://hubs.mozilla.com/docs).

## Additional Resources

* [Reticulum](https://github.com/mozilla/reticulum) - Phoenix-based backend for managing state and presence.
* [NAF Janus Adapter](https://github.com/mozilla/naf-janus-adapter) - A [Networked A-Frame](https://github.com/networked-aframe) adapter for the Janus SFU service.
* [Janus Gateway](https://github.com/meetecho/janus-gateway) - A WebRTC proxy used for centralizing network traffic in this client.
* [Janus SFU Plugin](https://github.com/mozilla/janus-plugin-sfu) - Plugins for Janus which enables it to act as a SFU.
* [Hubs-Ops](https://github.com/mozilla/hubs-ops) - Infrastructure as code + management tools for running necessary backend services on AWS.

## License

Hubs is licensed with the [Mozilla Public License 2.0](./LICENSE)
