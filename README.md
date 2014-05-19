CCRMA Poster
============

CCRMA Poster Beamer Theme.

- **Author**: jorgeh
- **Creation Date**: December 2013
- **Last Modification**: May 2014



Installation and Use
--------------------

This was developed for personal use, and no attempt to make it distributable have been made. If you would like to use it, simply clone (or download) the project and create your `<poster_name>.tex` file. A sample file `example.tex` is provided. The simplest thing you can do is to rename it and take it from there.

Two color themes are provided:

1. `beamerthemeCCRMAPoster.sty`: uses CCRMA "official" colors
2. `beamerthemeSUPoster.sty`: uses Stanford University official colors

Select the desired color theme in the `.tex` file by calling

    % \usetheme{CCRMAPoster}  % CCRMA colors
    \usetheme{SUPoster}       % Stanford colors


Customization
-------------

This should be considered just a starting point. Further customization can be achieved.

### Colors

To customize the colors, you could either edit `beamerthemeCCRMAPoster.sty` (or `beamerthemeSUPoster.sty`)

*Note:* due to beamer magic, you need to drop the `beamertheme` prefix and the extension `.sty` when setting the theme (e.g. `\usetheme{CCRMAPoster}`)


### Basic Layout

This is done in the `.tex` file (see `example.tex` for reference)


### Advanced Layout

For this you will need to change `beamerthemeJorgehPoster.sty`, but that is only for advanced users.