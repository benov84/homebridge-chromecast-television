
# Controller - Chromecast

This accessory will discover all chromecasts on the network and create a Television Accessory in HomeKit. Supported are Chromecast/Chromecast Ultra.

You can control the volume from Apple TV Remote in Control Center.

## Installation

```sh
npm i -g homebridge-chromecast-television
```
  
Add this to your config.json.
  
```json
"platforms":[
    {
      "platform": "ChromecastTelevision",
      "name": "ChromecastTelevision"
    }
]
```

## Credits
This project is based on [@homebridge-control-chromecast](https://github.com/yotamtal/homebridge-control-chromecast#readme)
