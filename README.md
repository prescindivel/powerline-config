# my powerline configs

![screenshot](Screen%20Shot%202018-03-02%20at%2010.53.06.png "screenshot")

## requirements:
- [powerline](http://powerline.readthedocs.io/en/master/installation.html)
- [patched fonts](https://github.com/powerline/fonts)

## how to install

clone this repository inside `~/.config/powerline`:
```shell
$ git clone https://github.com/victordev/powerline-config.git ~/.config/powerline
```

rename the tmux sample theme config:
```shell
$ mv ~/.config/powerline/themes/tmux/.default.sample.json ~/.config/powerline/themes/tmux/default.json
````

put the your gmail `username` and `password` to get inbox unread count and `location_query` to get weather info on `~/.config/powerline/themes/tmux/default.json` file.
