# post--interpreting-adversarial-attack

This repo is the front-end implementation of a potential [distil](https://distill.pub/) paper. The paper is currently a work in progress. Copy, visualizations, and results are all subject to change.  

Interpretability techniques are now mature enough to study various inputs to neural networks. 
We apply interpretability techniques to adversarial examples to understand how attacks unfold on a network — and develop more semantic tools to interpret network reasoning.

## Usage Instructions 
`npm run dev` to run a watching server.

`npm run build` to build, transpile, babel-ify and minify files.

Components are in `src`. The `.html` files are [svelte](https://svelte.technology/guide) components, the `.js` files are compilation endpoints that are also defined in `webpack.config.js`. These compiled endpoints are then consumed by hand authored `.ejs` files in `src`.
