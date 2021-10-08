# A demo app of [Fractal](https://fractal.build/), using the [Nunjucks adapter](https://github.com/frctl/fractal/tree/main/packages/nunjucks) and the default [Mandelbrot theme](https://github.com/frctl/fractal/tree/main/packages/mandelbrot)

Fractal is a tool to help you build and document web component libraries, and then integrate them into your projects.

Component (or pattern) libraries are a way of designing and building websites in a modular fashion, breaking up the UI into small, reusable chunks that can then later be assembled in a variety of ways to build anything from larger components right up to whole pages.

## Setup

**Firstly you need to have [Node](https://nodejs.org/en/download/) installed and then you can start the setup:**

Clone this repository and open the terminal within the project folder and run:
```bash
npm i
```
Then, you can run this command to build a CSS file with webpack:
```bash
npm run build
```
At the end you can start a local Fractal server:
```bash
fractal start --sync
```