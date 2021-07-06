# Wall-Pack
## _Dark themed wallpaper pack_

Most of theme wallpapers are taken from [wallhaven.cc](https://wallhaven.cc/). Thanks to all those beautiful people.

## I3 random wallpapers on startup

By adding this simple code, which uses [```feh```](https://github.com/derf/feh) image viewer to set wallpaper, in your I3 config file, it'll set random wallpapers every time the I3 is started.
Clone this repo to any location and change the directory in the code below.

```

exec --no-startup-id feh --randomize --bg-fill /home/user/Pictures/Wallpapers/*

```
