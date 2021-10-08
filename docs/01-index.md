This is a demo app of [Fractal](https://fractal.build/), using the [Nunjucks adapter](https://github.com/frctl/fractal/tree/main/packages/nunjucks) and the default [Mandelbrot theme](https://github.com/frctl/fractal/tree/main/packages/mandelbrot) (with [custom colors](https://fractal.build/guide/web/default-theme.html#configuration) though).

## Setup

**First, you need to have [Node](https://nodejs.org/en/download/) installed and then you can start the setup:**

-   Clone this repository, then, open the terminal within the project folder and run:
```bash
npm i
```
-   Then, you can run this command to build a CSS file with webpack:
```bash
npm run build
```
-   Then, you can start a local Fractal server:
```bash
fractal start --sync
```