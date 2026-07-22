# Forked
This was forked from [andreypopov/node-red-contrib-zigbee2mqtt](https://github.com/andreypopov/node-red-contrib-zigbee2mqtt) but that repo was last updated more than 18 months ago and the dependencies were horribly out of date and wouldn't cleanly install for me, I've since made improvements such as more state options to support ZigBee devices I own which I submitted a PR but given all the other unmerged PRs I doubt it'll be accepted any time soon.

# node-red-contrib-zigbee2mqtt-eb
[![platform](https://img.shields.io/badge/platform-Node--RED-red?logo=nodered)](https://nodered.org)
[![Min Node Version](https://img.shields.io/node/v/node-red-contrib-zigbee2mqtt-eb.svg)](https://nodejs.org/en/)
[![GitHub version](https://img.shields.io/github/package-json/v/evilbunny2008/node-red-contrib-zigbee2mqtt-eb?logo=npm)](https://www.npmjs.com/package/node-red-contrib-zigbee2mqtt-eb)
[![GitHub stars](https://img.shields.io/github/stars/evilbunny2008/node-red-contrib-zigbee2mqtt-eb)](https://github.com/evilbunny2008/node-red-contrib-zigbee2mqtt-eb/stargazers)
[![Package Quality](https://packagequality.com/shield/node-red-contrib-zigbee2mqtt-eb.svg)](https://packagequality.com/#?package=node-red-contrib-zigbee2mqtt-eb)

[![issues](https://img.shields.io/github/issues/evilbunny2008/node-red-contrib-zigbee2mqtt-eb?logo=github)](https://github.com/evilbunny2008/node-red-contrib-zigbee2mqtt-eb/issues)
![GitHub last commit](https://img.shields.io/github/last-commit/evilbunny2008/node-red-contrib-zigbee2mqtt-eb)
![NPM Total Downloads](https://img.shields.io/npm/dt/node-red-contrib-zigbee2mqtt-eb.svg)
![NPM Downloads per month](https://img.shields.io/npm/dm/node-red-contrib-zigbee2mqtt-eb)
![Repo size](https://img.shields.io/github/repo-size/evilbunny2008/node-red-contrib-zigbee2mqtt-eb)

Node-Red Nodes for Zigbee2mqtt connectivity.

# Install
You should do the following:
```
npm install -g node-red
mkdir -p /opt/node-red
useradd -d /opt/node-red -M node-red
chown -R node-red: /opt/node-red
su -s /bin/bash - node-red
mkdir -p .node-red
cd .node-red
node-red admin init
```

Next edit the settings.js to match your server
```nano settings.js```

Finally install this module
```
npm install node-red-contrib-zigbee2mqtt-eb
```
and then you can start Node Red by doing
```
cd ..
node-red
```

# Available nodes
* zigbee2mqtt-in: listen to device
* zigbee2mqtt-get: get current value of device
* zigbee2mqtt-out: send command to device
* zigbee2mqtt-bridge: logs, options, other events

Extra features:
* groups support
* network map generation

<img src="https://github.com/evilbunny2008/node-red-contrib-zigbee2mqtt-eb/blob/main/readme/1.png?raw=true">
<img src="https://github.com/evilbunny2008/node-red-contrib-zigbee2mqtt-eb/blob/main/readme/2.png?raw=true">
<img src="https://github.com/evilbunny2008/node-red-contrib-zigbee2mqtt-eb/blob/main/readme/3.png?raw=true">
<img src="https://github.com/evilbunny2008/node-red-contrib-zigbee2mqtt-eb/blob/main/readme/4.png?raw=true">
<img src="https://github.com/evilbunny2008/node-red-contrib-zigbee2mqtt-eb/blob/main/readme/5.png?raw=true">

# Support
Developing and supporting this plugin needs time and efforts. Appreciate your support on [Patreon](https://www.patreon.com/bePatron?u=12661781). Here, you can sign up to be a member and help support my project.
