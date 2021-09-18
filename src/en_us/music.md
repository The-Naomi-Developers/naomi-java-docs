# Category: **Music**

- [`/play <query>`](/en_us/music.html#play-query)
- [`/repeat <choice>`](/en_us/music.html#repeat-choice)
- [`/stop`](/en_us/music.html#stop)
- [`/stop`](/en_us/music.html#stop)
- [`/pause`](/en_us/music.html#pause)
- [`/skip`](/en_us/music.html#skip)
- [`/rewind <time>`](/en_us/music.html#rewind-time)
- [`/rewind <time>`](/en_us/music.html#rewind-time)
- [`/volume <new_volume>`](/en_us/music.html#volume-new_volume)
- [`/nowplaying`](/en_us/music.html#nowplaying)

### `/play <query>`
Start playing a track or add it to the queue. You must be in the voice channel to use this command.

> **Cooldown**: 5 seconds  
> **Required permissions**: No

### `/repeat <choice>`
Controls the repeat mode of the track. If the `choice` argument is equal to `Yes-s-s`, the repeat mode will be enabled. Selecting `No` will disable the track repeat mode.

> **Cooldown**: 5 seconds  
> **Required permissions**: No

### `/stop`
Stop playing music on this server. You must be be in the voice channel to use this command.

> **Cooldown**: 5 seconds  
> **Required permissions**: No

### `/pause`
Unpause or pause the playback. If playback is paused, it will unpaused, if not, it will paused.

> **Cooldown**: 5 seconds  
> **Required permissions**: No

### `/skip`
Skip the current track and start playing the next track. If the current track is the last track in the queue, playback will stop.

> **Cooldown**: 5 seconds  
> **Required permissions**: No

### `/rewind <time>`
Rewind the track to a specific moment. To rewind, use the following time format: `mm:ss`, where `m` is minutes, `s` is seconds.   
For example: `/rewind 2:35`

> **Cooldown**: 5 seconds  
> **Required permissions**: No

### `/volume [new_volume]`
Change the volume level. The maximum volume level is 200%. To find out what volume the player is currently set to, use the `/nowplaying` command.

> **Cooldown**: 5 seconds  
> **Required permissions**: No

### `/nowplaying`
Information about the current track as well as the play queue. Displays the playback progress bar, volume, player position, track duration, track title, source link, and more.

> **Cooldown**: 5 seconds  
> **Required permissions**: No
