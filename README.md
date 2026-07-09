# Kapadokya Tour 2026 Webpage

This folder contains a simple one-page travel website.

## Files

- `index.html`: Page structure
- `styles.css`: Visual design and responsive layout
- `script.js`: Route map, programme timeline, and photo gallery data
- `images/`: Put your own photos here

## How to add your real trip details

1. Open `script.js`.
2. Update the `trip.dateRange`, `trip.totalDays`, and `trip.city` values.
3. Replace items inside `trip.stops` with your real route data.
4. Replace items inside `trip.programme` with your day/week activities.
5. Put your images in `images/` and update `trip.photos` with local paths.

Example local photo path:

```js
{ src: "images/day-01-goreme.jpg", caption: "Arrival in Goreme" }
```

## Run locally

Open `index.html` in your browser.
