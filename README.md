## Welcome to ColorAPI!
ColorAPI shows a square image for any hex code provided.

## Supported File Types

- svg
- webp
- png
- jpeg/jpg

## Using ColorAPI
ColorAPI uses the following URL structure:
```
https://colorapi.glitch.me/HEXCODE.FILETYPE
```

For example:
```
https://colorapi.glitch.me/fff.webp
```

## How it works
ColorAPI takes the provided hex code and inserts it into SVG code, then if necessary, converts it to an image file using [svg-to-img](https://npmjs.org/package/svg-to-img). ColorAPI is powered by [express](https://expressjs.com).

---

ColorAPI was created by [advaith](https://advaith.fun) originally for use in [BeepBot](https://beepsite.glitch.me) and was inspired by [color.dyno.gg](https://color.dyno.gg/color/fff/256x256.png).