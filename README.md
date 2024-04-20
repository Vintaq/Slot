

## Features

- Fully responsive for great UX on mobile, web & fullscreen mode.
- Autoplay functionality, which keeps running even if the game window is in background.

## Installation, Build & Deployment

1. Clone repository
2. Run `npm install`
   - _Development_: run `npm start` and go to `http://localhost:8080`
   - _Production_: run `npm run build` and serve from `/dist`

| Property      | Description                                                                                                                            | Default   |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| `inverted`    | Controls visual spinning direction of reels. If false, reels will spin from bottom to top. If true, reels will spin from top to bottom | false     |
| `onSpinStart` | Callback function invoked when spin starts with symbols pattern array `(symbols) => void`.                                             | undefined |
| `onSpinEnd`   | Callback function invoked when spin ends with symbols pattern array `(symbols) => void`.                                               | undefined |

## Credits

Icons are created by [KPD Media](https://dribbble.com/shots/3517520-Star-Wars) and can be used for private and commercial purposes with no attribution required ([check license here](https://iconstore.co/icons/10-star-wars-icons/)).
