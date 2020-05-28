# Flowplayer files v2.5.0

![flowplayer logo](https://flowplayer.com/user/pages/images/logo-blue.png)

Contains the main files needed to get started with Flowplayer

https://flowplayer.com/features/player

Files downloaded from: https://flowplayer.com/developers/player/embedding#host-player-assets-on-your-own...

## Use

You can include plugins like this:
```
import flowplayer from 'flowplayer-files/lib/flowplayer.min.js';
import chromecast from 'flowplayer-files/lib/plugins/chromecast.min.js';
import cuepoints from 'flowplayer-files/lib/plugins/cuepoints.min.js';
import subtitles from 'flowplayer-files/lib/plugins/subtitles.min.js';

flowplayer.extensions.push(chromecast);
flowplayer.extensions.push(cuepoints);
flowplayer.extensions.push(subtitles);

const api = flowplayer('.player', config);
```

## Note on the version of this package

This repository will follow the first 2 digits of the flowplayer semantic versioning and the third image will be reserved for bug fixes to this package itself.
eg: flowplayer version 2.2.0.
* This package: 2.2.1
* 2.2 from flowplayer
* .1 means one fix after we've updated to flowplayer 2.2.0

The version number in the readme will always reflect the complete version tag of the flowplayer files
