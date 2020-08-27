# Flowplayer files v2.5.9

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
