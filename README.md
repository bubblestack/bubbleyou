# bubbleyou

bubbleyou is a bash script (also systemd service) which mainly focus to re-stream RTPS IP cameras, but of course can stream any video/audio inputs ( ip camera, CCTV, VLC...) using ffmpeg. bubbleyou is part of bubblestack project.

### features:
+ Stream any video source to youtube live.
+ Stream and save videos simultaneously.
+ Can by run as daemon/systemd service or script.
+ Comes with easy adjustable config file.
+ Can check streaming status on youtube.


### usage:
```bash
$ bubbleyou {start|stop|status|check|restart}
``` 

### example:
```bash
$ bubbleyou check
We are Live on Youtube: https://www.youtube.com/watch?v=kolFLCQ_K48

### License:
bubbleyou is part of bubblestack project and is released under the [MIT License](http://www.opensource.org/licenses/MIT).

