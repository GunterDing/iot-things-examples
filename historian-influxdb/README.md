# Bosch IoT Things - Historian based on InfluxDB

This example shows a simple historian collector service that pushes modifications of Things to an InfluxDB.
Based on this a dashboard using Grafana can be created that visualizes the collection data.

# Prepare

## Use an existing or request a new Bosch IoT Things service instance

<a href="https://things.apps.bosch-iot-cloud.com/dokuwiki/doku.php?id=002_getting_started:booking:booking">Book the Bosch IoT Things cloud service</a>

## Configure your settings

Set your credentials in the file "config.json". You can copy "config.json-template" as template and fill out placeholders.

# Build and Run

```
npm install
npm run build
npm run start
```

If you need to access the Internet using a Proxy configuration, please make sure to set the environment variable HTTPS_PROXY.

# License
See the iot-things-examples top level README.md file for license details.