# Sass processing with Atomic Design explained

Basic template with Eleventy, LiquidJS & Sass processing

eleventy.config.js:
- addWatchTarget in ./src/sass/
- addPassthroughCopy in ./src/assets
- input in src
- output in _site
- includes in _components
- layouts in _layouts

package.json:
- @11ty/eleventy 2.0.1
- sass 1.69.0