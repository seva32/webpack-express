Running `npm run buildDev`, Javascript, HTML, and CSS files are unminified and not uglified. Hot Module Reloading is enabled via `webpack-dev-middleware` and `webpack-hot-middleware`.
Running `npm run buildProd`, Javascript, HTML, and CSS files are all minified and uglified, and images are encoded as Base64 directly into the CSS file.
