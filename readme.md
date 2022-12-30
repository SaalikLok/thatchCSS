# ThatchCSS

### Development

ThatchCSS is developed with the help of [Sass](https://sass-lang.com/). Ensure you have it installed.

After cloning the repository, ensure that any changes made in the src files are watched:

```
sass src/index.scss thatch.css --watch
```

### Motivation

Sass is only used as a nicety in development (yes, I love double-slash comments and nesting).

This doesn't stop anyone from copying any and all css from the `index.css` file and tweaking it for a project's particular needs.

Thatch isn't meant as a one-size-fits-all solution, but for my need in particular, it's a one-size-fits-most solution. It's also a great starting point for easy layouts that can then be tweaked as needed.

It's intentional that this package is available as files to be read on GitHub, and not as an abstracted npm module.
