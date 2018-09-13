# Pitfallse

* use a v8 docker image
* enabel [Home Assistant API](https://www.home-assistant.io/components/api/) if you are not on HASS.io
* the mounted data folder needs to be writable for 1001:1001
* enable palette `node-red-contrib-home-assistant`
* enable project dependency `node-red-contrib-home-assistant`
* deploy one flow if you get `Cannot GET /homeassistant/entities`
