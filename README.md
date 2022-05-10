# obs-browser-sources

Utility browser sources for OBS Studio.

## pomodoro.html

Universal 50/10 pomodoro timer with auto scene switcher.

Every hour, it shows remained work time from 00 to 50 minutes, then shows remained break time from 50 to 00 minutes.

![](images/pomodoro.png)

### Basic usage

Add a browser source with the following URL:

- https://r7kamura.github.io/obs-browser-sources/pomodoro.html

### Advanced usage

If you set **ADVANCED** permission ("OBSへの高度なアクセス" in Japanese) and there are scenes named `Work` and `Break`,
this browser source will automatically switch between the scenes according to the timer.
