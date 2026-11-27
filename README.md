# Everyspace demo

The earlier Everyspace prototype: a single-file app that runs entirely in the browser with demo data (saved in your browser's local storage). Connections to other sites, payments and bookings are simulated.

**Demo:** https://milessilverman.github.io/everyspace-demo/

The real Everyspace app lives in [milessilverman/everyspace](https://github.com/milessilverman/everyspace):

- Home (address in, property profile out): https://milessilverman.github.io/everyspace/
- Host Console (real, signed-in): https://milessilverman.github.io/everyspace/host/

## What is here

| File | What it is |
|---|---|
| `index.html` | The whole demo app (routes are in-page, e.g. `#/map`, `#/host`). |
| `everyspace.html` | An identical copy, kept so old links still work. |
| `tests/domain.test.mjs` | Tests for the demo's pricing, sync and privacy rules. They load the code straight out of `index.html`. |

## Tests

```bash
node --test tests/*.test.mjs
```

## History

This repository was split out of `milessilverman/everyspace` on 2026-11-27 with the demo files' commit history. Prices, fees and event figures in the demo are illustrative planning numbers, not market data.
