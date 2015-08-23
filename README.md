# Sassy Accio

A small, lightweight collection of Sass incantations.

Naturally, adjustments need to be made on a case-by-case basis - especially with the variables
file, which most of the values are just placeholders.

A typical project structure has all of the Sass files in a `src/` directory where I split up `styles/` and `scripts/`.
Inside `styles/` I usually place the partials in a `partials/` directory with the main `style.scss` file at the root of
the `styles/` dir. The `style.scss` just pulls in all of the partials via `@import` calls.

A visual example of the dir structure would look something like the
following (you can also see this in the [Sip](https://github.com/danielwrobert/sip] repo):

![Src Tree](https://github.com/danielwrobert/sassy-accio/blob/screenshots/screenshots/src-tree.png "Src Tree")

* Note: These do not include any vendor-prefix mixins. I would advise pairing these with [Autoprefixer](https://github.com/ai/autoprefixer).
