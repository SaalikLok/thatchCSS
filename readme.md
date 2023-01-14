# ThatchCSS

### Development

ThatchCSS is developed with the help of [Sass](https://sass-lang.com/). Ensure you have it installed.

After cloning the repository, ensure that any changes made in the src files are watched:

```
sass src/index.scss thatch.css --watch
```

### Motivation

Thatch isn't meant as a one-size-fits-all solution, but for my need in particular, it's a one-size-fits-most solution. It's also a great starting point for easy layouts that can then be tweaked as needed.

It's intentional that this package is available as files to be read on GitHub, and not as an abstracted npm module.

With basic CSS knowledge, it's easy for me and you to tweak Thatch styles for your particular project, but have a nice base to work with.

It's also easy to rename the classes so you don't have any "thatch" mentioned in your repository. (Gotta keep it semantic, yall!)


### Available Resources

`thatch-container` is a container with 4 variations:

- `thatch-container--super-narrow`
- `thatch-container--narrow`
- `thatch-container`
- `thatch-container--full`

`thatch-split` elegantly splits the children of the element into two even columns, and has a generous mobile breakpoint by default.

`thatch-grid` allows setting up a grid of _x_ number of elements. It has 4 variations:

- `thatch-grid--2x`: a two column grid
- `thatch-grid--3x`: a three column grid
- `thatch-grid--4x`: a four column grid
- `thatch-grid--auto`: an automatic grid
