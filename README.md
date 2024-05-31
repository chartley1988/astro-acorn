# Acorn Template

## Getting Started

## What does this template include?

This template is supposed to be pretty lean. It includes:

- CSS reset
- Some base styles and custom properties
- Layout tools from EveryLayout in the form of web components
- Shoelace - though nothing is included by default, it is setup to easily add
  components

### EveryLayout

[EveryLayout - Homepage](https://every-layout.dev/) \
EveryLayout is a book that provides methods of responsive design without media
queries. In this case, they are implemented with web components. They're
imported within the base layout, and can be used in any component within that
layout without importing them. They're used like a standard HTML Element.

### Shoelace Web components

[Shoelace.style - Homepage](https://shoelace.style/) \
Shoelace is a library of web components. Use for things like carousels and
switches. To modify the styles, you can generally get away with adding design
token properties to a CSS file. `./src/config/properties.css` is setup for CSS
custom properties.

The CSS files from shoelace are in `./shoelace/`. Copy the styles that are
needed for any component for the app. If many shoelace components are used, it
may be worth including the whole stylesheet.

### Generic Components needed for most projects

- [Header](src/components/Header.astro)
- [Footer](src/components/Footer.astro)
