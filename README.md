# Neon Hands

Open your palm and your fingers light up with glowing neon wires. Raise both hands and the wires connect, hanging between your fingertips like real cables.

It's a single HTML file that runs entirely in your browser, with no install and no build step. Your camera video stays on your device.

## Demo

Live page: https://JC-glitchsys.github.io/neon-hands/

*(Works once GitHub Pages is turned on for this repo.)*

## Features

- **Full-screen camera:** the camera fills the whole window, with no buttons in the way.
- **Neon finger wires:** open one palm and cyan wires trace the bones of each finger, with a soft spark running along them.
- **Dangling wire ends:** every fingertip has a loose wire that swings and settles with gravity as you move.
- **Hanging cables between hands:** open both palms and matching fingertips are joined by smooth cables that sag and sway.
- **Fade in and out:** wires appear when your palm opens and fade away when you close it.

## How to use

1. Open the page in Chrome, Edge or Safari, with internet on.
2. Click **Open Camera** and allow camera access.
3. Hold up an open palm, with fingers spread and facing the camera.
4. Raise your second hand to connect them.

### Keyboard shortcuts

| Key | Action |
| --- | --- |
| `F` | Toggle fullscreen |
| `S` | Save a screenshot (PNG) |

## Run it locally

The camera needs `https` or `localhost`, so opening the file directly can get blocked. Serve the folder instead:

```bash
python -m http.server
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

1. Name the file `index.html` and put it in the repo root.
2. Go to **Settings → Pages**.
3. Set the branch to `main` and the folder to `/ (root)`, then save.

## Built with

- [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) for hand tracking, loaded from a CDN
- HTML Canvas for the neon glow and a simple rope physics simulation for the hanging wires
- [Google Fonts](https://fonts.google.com/) (Great Vibes, Inter) on the start screen

## Tips

- Use bright, even lighting. Dim rooms make the tracking flicker.
- Keep your hand roughly upright and facing the camera.
- If it feels slow, close other heavy tabs and try Chrome or Edge.
- If the camera is blocked, check your browser's site permissions.

## Author

Made by [Jonaidah Caris](https://github.com/JC-glitchsys).