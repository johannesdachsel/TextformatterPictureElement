# TextformatterPictureElement

Module for the fabulous [Processwire CMS](http://processwire.com) that replaces all `<img>` elements in a textarea with configurable `<picture>` elements and also provides a fallback `<img>` element.

## How to use it

The module allows configuring multiple `<source>` elements, each with an image size and a media query. Go to the module configuration page and enter each desired `<source>` element like so: size=query or e.g. 800=(min-width: 45em).

You can also specify the size of a fallback image.

## How it works

The module replaces all `<img>` elements with the configured `<picture>`element when the field is rendered.