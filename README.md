# Gradience

Animated gradient background with a curtain wipe transition — a personal website template.

## Usage

1. Open `index.html` in a browser
2. Click palette dots at the bottom to switch color schemes
3. Scroll through the page content

## Customization

Edit the `CFG` object at the top of `index.html`:

```js
const CFG = {
  defaultColors: ['#0f0c29','#302b63','#24243e'],  // initial gradient
  angle: 135,                                        // gradient angle
  palettes: [                                        // palette swatches
    { name: 'Abyss',  colors: ['#0f0c29','#302b63','#24243e'] },
    { name: 'Navy',   colors: ['#1a1a2e','#16213e','#0f3460'] },
    // ...
  ],
};
```

## Features

- Zero dependencies — no frameworks, no JS libraries
- Fixed gradient background with scrollable content
- Curtain transition via clip-path diagonal wipe
- Real-time palette switching
- Dark/light theme support

## License

MIT
