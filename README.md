# Length Unit Converter

A tiny single-file frontend app that converts between **km, m, cm, foot, inch, and mile**.

> AI-generated test code — written by Claude (Claude Code CLI) as a quick demo.

## Usage

Open `index.html` in any modern browser. Enter a value, pick the source unit, and the other five units update live.

- No build step
- No dependencies
- One HTML file (inline CSS + JS)

## Conversion factors

All conversions route through meters:

| Unit | Meters |
|------|--------|
| 1 km | 1000 |
| 1 m  | 1 |
| 1 cm | 0.01 |
| 1 ft | 0.3048 |
| 1 in | 0.0254 |
| 1 mi | 1609.344 |
