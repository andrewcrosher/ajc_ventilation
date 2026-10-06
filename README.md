# VentiSmart

VentiSmart is a personal project: a small browser-based dew point and ventilation advisor. It compares outdoor forecast conditions with an indoor dew point target to help identify times when ventilation may help reduce indoor moisture.

The app is a single static HTML page and does not require a build step or a server-side component.

## Features

- Estimates dew point from temperature and relative humidity.
- Shows a ventilation recommendation based on the outdoor and indoor target dew points.
- Displays hourly forecast information in a chart and table.
- Lets you adjust indoor settings, forecast location, and forecast model.
- Includes a manual scenario tool and a 10-minute purge timer.
- Shows a refresh indicator while forecast data is being updated.

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a browser, or open the repository in VS Code and use a local preview extension such as Live Preview.
3. Allow the page to access the internet so it can load its libraries and request forecast data.

The app requests hourly temperature and relative humidity data from the [Open-Meteo API](https://open-meteo.com/). If a forecast request fails, it displays generated fallback data instead.

## Publish with GitHub Pages

GitHub Pages hosts this static app directly from the repository at [andrewcrosher.github.io/ajc_ventilation/](https://andrewcrosher.github.io/ajc_ventilation/)
