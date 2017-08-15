# Clapton ⛱️

> Yet Another Open Source Media Player

![Example](assets/images/clapton.png)

Clapton is a Open Source Media Player witch runs on [Clappr](https://github.com/clappr/clappr) and [Electron](https://github.com/electron/electron).

## Features

- Another Open Source Media Player 🦄 🦄 🦄
- Hackable
- Support stream of Torrents
- Allows multiples Source (automatic playlist)
- Chromecast Integration ([issue #6](https://github.com/raphamorim/clapton/issues/6))
- Airplay Integration ([issue #2](https://github.com/raphamorim/clapton/issues/6))
- [Suggest a feature](https://github.com/raphamorim/clapton/issues/new)

## Hackable

Clapton can load local Clappr Plugins. You only need to specify a `~/.claptonconfig` on your `$HOME`

You can create running:

```bash
$ touch $HOME/.claptonconfig
```
Sample:

```json
{
  "defaults": {
    "theaterSource": "absolute-path-to-my-video",
    "colors": {
      "primaryColor": "blue",
      "secondColor": "red"
    }
  },
  "plugins": [
    "absoulute-path-to-my-plugin",
    "absoulute-path-to-my-second-plugin",
  ]
}
```

Note: `.claptonconfig` is optional.
Note2: Plugins will be available only at `>= Clapton 0.2.0`

## Create a Plugin for Clapton

Plugins will be available only at `>= Clapton 0.2.0`

#### [Generator-Clappr-Plugin](https://github.com/clappr/generator-clappr-plugin)

## Migrating Clappr External Plugins to Clapton

Most part of current plugins are being tested on `Clapton 0.2.0`. Help us to integrate.

|Plugin         |Status|URL|
|-----------------------|---------------------------------------|--------------------------------------------------------|
|Thumbnails on seekbar| WIP| https://github.com/tjenkinson/clappr-thumbnails-plugin |
|Markers       | WIP| https://github.com/tjenkinson/clappr-markers-plugin |
|Level Selector| WIP| https://github.com/clappr/clappr-level-selector-plugin |
|360 videos| WIP| https://github.com/thiagopnts/video-360 |
|Chromecast| WIP| https://github.com/clappr/clappr-chromecast-plugin |
|DASH with shaka| WIP| https://github.com/clappr/dash-shaka-playback |
|Clappr Stats | WIP| https://github.com/leandromoreira/clappr-stats |
|Pause while far| WIP| https://github.com/leandromoreira/clappr-pause-tab-visibility |
|RTMP           | WIP| https://github.com/clappr/clappr-rtmp-plugin |
|Picture-in-Picture | WIP| https://github.com/tjenkinson/clappr-pip-plugin |
|HLS+P2P        | WIP | http://bem.tv |
|Comments on seekbar| WIP | https://github.com/Metrakit/clappr-comment-plugin |
|Voice control| WIP | https://github.com/flavioribeiro/clappr-speech-control-plugin |
|Dash           | WIP | https://github.com/shankardevy/clappr-dash-plugin | |
|Youtube        | WIP | https://github.com/towerz/clappr-youtube-playback |
|VAST Ad plugin | WIP | https://github.com/vix-simplex/clappr-ad-plugin |

## Supported Formats

Version       |HLS|MP4|MP3|WEBM| DASH | RTMP | JPG/PNG/GIF |
-------------|---|---|---|----|------|------|-------------|
 0.1.8 | ✔ | ✔ | ✔ |  ✔ | ![dash](http://flv.io/external3.png) | ![rtmp](http://flv.io/external3.png) | ✔

![rtmp](http://flv.io/external3.png) means that the support is made by an external plugin.

## Credits

Clapton was created by [@raphamundi](https://twitter.com/raphamundi).

Powered by [Electron](https://github.com/electron/electron), [Clappr](github.com/clappr/clappr) and [WebTorrent](https://github.com/webtorrent/webtorrent).

