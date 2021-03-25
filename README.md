
# Chromecast Television Accessory

This plugin will discover all chromecasts on the network and create a Television Accessory. Supported are Chromecast/Chromecast Ultra.

Switching On/Off will Play/Pause the stream. You can control the volume from Apple TV Remote in Control Center.

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
