# T3 Code Themes

A small collection of custom JSON themes for [T3 Code](https://github.com/pingdotgg/t3code).

## Pixel Quest Koi

A dark theme with a pixel-art koi lake. The water shifts from teal shallows to a darker center, with scattered rocks and four koi swimming around the larger stones. Each koi makes a small pixel ripple near its head when it pauses to feed. Pixel-edged chat bubbles keep messages readable over the animated scene.

Theme file: [`pixel-quest-koi.json`](pixel-quest-koi.json)
Theme ID: `pixelkoi`

## Koi Blue

A light-blue theme with a pastel palette and chat bubbles.

Theme file: [`koi-blue.json`](koi-blue.json)
Theme ID: `koi-blue`

## Install

In T3 Code, open **Settings → Appearance → Import** and select a theme JSON file.

To install from the command line, copy the JSON file into `~/.t3/userdata/themes/`, then select the theme by ID:

```sh
t3 theme set pixelkoi
```

Use `t3 theme set koi-blue` to select Koi Blue.
