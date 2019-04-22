# Pitfalls

* use a v8 docker image
* enabel [Home Assistant API](https://www.home-assistant.io/components/api/) if you are not on HASS.io
* the image users runs has id:group 1001:1001, take care of this
* enable palette `node-red-contrib-home-assistant`
* enable project dependency `node-red-contrib-home-assistant`
* deploy one flow if you get `Cannot GET /homeassistant/entities`
