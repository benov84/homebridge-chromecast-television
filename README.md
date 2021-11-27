
# Chromecast Television Accessory

This plugin will discover all chromecasts on the network and create a Television/Streaming Accessory. Supported are Chromecast/Chromecast Ultra.

Switching On/Off will stop the stream. You can control the volume and play/pause from Apple TV Remote in Control Center.

## Installation

```sh
npm i -g homebridge-chromecast-television
```
  
Add this to your config.json.
  
```json
"platforms":[
    {
      "platform": "ChromecastTelevision",
      "name": "ChromecastTelevision",
      "category": "TELEVISION"
    }
]
```

You can specify category for HomeKit accessory - TELEVISION, TV_STREAMING_STICK, TV_SET_TOP_BOX, APPLE_TV. This does not change the device functions, but allows you to choose how the device is displayed in the Home app.
![Image](https://user-images.githubusercontent.com/8211291/123853650-b295ad80-d8eb-11eb-8d75-9ff557671ec9.jpeg)

## Add to HomeKit
This plugin adds the Chromecast as an external device. Once the plugin is configured you will have to add a new accessory in the Home app using the same code as your homebridge instance.

Due to an Apple limitation TV-type devices cannot be controlled in 3rd party HomeKit apps such as Eve.

## Credits
This project is based on [@homebridge-control-chromecast](https://github.com/yotamtal/homebridge-control-chromecast#readme)
