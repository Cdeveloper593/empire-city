# EMPIRE CITY

A scroll-scrubbed flight through a miniature New York City, from dawn to night. A static HTML page uses the shared `scrub-engine.js` engine, with system fonts, no external libraries, and no build step. Stills serve as posters while clips load and as the reduced-motion experience.

The six sections, in order:

1. **The Arrival** (`arrival`) — Manhattan at dawn.
2. **Central Park** (`central-park`) — Bow Bridge and the lake in the morning.
3. **Brooklyn Bridge** (`brooklyn-bridge`) — cables and DUMBO in golden afternoon light.
4. **Times Square** (`times-square`) — billboards and yellow cabs at dusk.
5. **The Night Skyline** (`skyline-night`) — lit towers and the night ferry.
6. **Your World Next** (`finale`) — an invitation to [start your world with Cerium](https://cerium-web-development.vercel.app/).

## Run locally

Serve this folder with any static server, for example:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. Enable JavaScript for the scroll experience; a dawn poster and description remain available without it.

## Asset layout

```text
index.html                 Page, theme, and scene configuration
scrub-engine.js            Shared scroll engine
assets/scene1.webp … scene6.webp       Six section posters
assets/vid/scene1.mp4 … scene6.mp4     Six scene clips
assets/vid/conn1.mp4 … conn5.mp4       Five connecting flights
```

Place the finished video files at these exact paths to complete the flight sequence.
