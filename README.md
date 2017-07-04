# svelte-nested-components-test

Just a quick bit of example code, almost the same as [the nested one on the Svelte REPL](https://svelte.technology/repl?version=1.23.4&example=nested-components), with a few extra experiments (e.g. using `{{yield}}` and having multiple copies.

Does not require node.js, or node_modules, or any bundler.

## To Build

- `svelte compile` the .html files under `components` to the dist folder
- copy the index.html file there
- this can be done with `npm run build` or `npm run dev` for the development version

## To Run

Build outputs to 'dist' subfolder, just open `dist/index.html` in any browser.
