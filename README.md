# Birthday Gift 🎂

An interactive, animated birthday page you can send someone special. Lights turn on, balloons fly in, candles light up, cake gets cut, and a scrolling message plays out — all triggered by a row of buttons at the bottom.

## Features

- Twinkling bulb lights
- Custom name banner and floating letter balloons
- Animated birthday cake with flickering candles
- Cut the Cake — candles blow out and the cake splits to reveal a slice
- Scrolling birthday message
- Background music

## Getting started

No build step — it's plain HTML/CSS/JS.

```bash
git clone https://github.com/bikal1000/bikal1000.github.io.git
cd bikal1000.github.io
```

Open `index.html` in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customizing

- **Name / letters**: edit the `.balloons` divs in [index.html](index.html)
- **Message**: edit the `<p>` lines inside `.row.message` in [index.html](index.html)
- **Music**: replace [hbd.mp3](hbd.mp3) with your own track (keep the filename or update the `<source>` tag)
- **Photo**: replace [images/bd1.jpg](images/bd1.jpg)
- **Colors / styling**: [css/stylesheet.css](css/stylesheet.css) and [css/cake.less](css/cake.less)

## Project structure

```
index.html          markup + button sequence
effect.js            jQuery interactions/animations for each step
css/stylesheet.css   layout, bulbs, balloons, buttons, cake-cutting
css/cake.less        cake shape/candle styling
css/loading.css       loading screen
images/               banner, balloons, bulbs, photo
hbd.mp3               background song
```

## Contributing

Issues and PRs welcome — new animations, mobile fixes, and accessibility improvements are all fair game.

## License

MIT
