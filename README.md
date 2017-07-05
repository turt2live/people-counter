# people-counter

[![Greenkeeper badge](https://badges.greenkeeper.io/turt2live/people-counter.svg)](https://greenkeeper.io/)

[![TravisCI badge](https://travis-ci.org/turt2live/people-counter.svg?branch=master)](https://travis-ci.org/turt2live/people-counter)

Uses Camlytics to show how many people are in certain areas.

# Install

1. Install Camlytics and add your cameras
2. Set up tripwires for your areas
3. Copy `config/default.yaml` to `config/production.yaml`
4. Edit `config/production.yaml` to set the tripwire configurations
5. Run the application with `NODE_ENV=production node index.js` (TODO: Windows instructions)
