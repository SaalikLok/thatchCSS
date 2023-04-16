# ThatchCSS

![thatch-roof](/thatch.png)

A few simple and reusable layout classes.

## Usage

Find the css you need in `thatch.css`. Feel free to copy any or all of the CSS there.

#### Container

`thatch-container` is a container with 4 variations that are expressively named:

- `thatch-container--super-narrow`
- `thatch-container--narrow`
- `thatch-container`
- `thatch-container--full`

#### Split

`thatch-split` elegantly splits the children of the element into two even columns, and has a generous mobile breakpoint by default.

#### Grid

`thatch-grid` allows setting up a grid of _x_ number of elements. It has 4 variations:

- `thatch-grid--2x`: a two column grid
- `thatch-grid--3x`: a three column grid
- `thatch-grid--4x`: a four column grid
- `thatch-grid--auto`: an automatic grid


## Motivation

I made Thatch for me, but think it could be useful to you too!

Thatch isn't meant to be a one-size-fits-all solution, but it could be a one-size-fits-most solution. It's also a great starting point for easy layouts that can then be tweaked as needed.

It's intentional that these files are just hosted on GitHub, and not abstracted into an npm module.

With basic CSS knowledge, it's easy for me and you to tweak Thatch styles for your particular project, but have a nice base to work with.

It's also easy to rename the classes so you don't have any "thatch" mentioned in your repository. (Gotta keep it semantic, yall!)

It's called Thatch because I intend on keeping this project simple, building with down-to-earth tools close to web development roots. Like a thatched hut, this project can also change over time, and be adjusted relatively easily, unlike a massive (and ugly) concrete structure.


## Development

If you plan to fork this repo or develop locally, know that ThatchCSS is developed with [Sass](https://sass-lang.com/). Ensure you have it installed. (I've been testing with Dart Sass).

After cloning the repository, ensure that any changes made in the src files are watched:

```
sass src/index.scss thatch.css --watch
```

MIT License.
by [Saalik](https://saaliklok.com)
