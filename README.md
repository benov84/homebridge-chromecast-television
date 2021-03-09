
# Controller - Chromecast

This accessory will discover all chromecasts on the network and create a Television Accessory.

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
