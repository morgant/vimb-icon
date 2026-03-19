<p align="center"><img src="https://raw.githubusercontent.com/morgant/vimb-icon/refs/heads/main/.github/images/vimb-transparent-512x512.png" ALT="Vimb icon (unofficial)" /></p>

# Vimb icon

by Morgan Aldridge <morgant@makkintosshu.com>

## OVERVIEW

An __unofficial__ application icon created for
[Vimb](https://github.com/fanglingsu/vimb), the Vim-like web browser, because
it doesn't have an official icon and I couldn't find one.

This project contains the original Inkscape SVG file which can be exported to
whichever format/resolution/etc. you need.

## DESIGN & COMPONENTS

I just wanted something that looked similar to the [Vim](https://www.vim.org/)
logo, but indicated that is _actually_ a web browser.

1. I started with the official Vim logo, specifically:
    [`vimlogo.svg`](originals/vimlogo/README.md)
2. Since it is built around [WebKitGTK](https://webkitgtk.org/), I checked
    for an official logo
    * Unfortunately, the WebKitGTK project doesn't have its own and the
      official [WebKit](https://webkit.org/) logo is [a trademark of
      Apple Inc.](https://webkit.org/terms-of-use/)
    * I'm not a huge fan of the current WebKit logo anyway, plus the design
      language clashes with the Vim logo's design
3.  Instead, I looked for an appropriately licensed 'compass' icon (more
    Safari/WebKit-like) to incorporate into the Vim logo, finding the
    [PrimeIcons](https://github.com/primefaces/primeicons/) project,
    specifically: [`compass.svg`](originals/compass/README.md)
4.  I manualy separated and recombined the Vim logo's components with the
    compass asset in Inkscape, ultimately making the following design
    decisions:
    * Preserving Vim logo's more traditional "green tile", thick lines, and
      solid white outline
    * Keeping only the Vim logo's large, gray, capital 'V' (vee), dropping the
      smaller letters 'i' & 'm'
    * Applying the 'compass' icon the "green tile" in a darker green, rotated
      slightly so that the compass needle aligns with the angle of the large,
      gray, Vim vee's [vertex][type-anatomy]
    * Scaling down and repositioning the gray Vim vee and over the "green
      tile" such that:
        * The vee's [head serif][type-anatomy] are centered around the pivot
          point (pin?) of the compass needle
        * The vee covers the edges of the bottom half of the compass needle,
          revealing the needle in its [vertex][type-anatomy]
        * The [crotch][type-anatomy] of the vee still extends beyond the
          bounds of the "green tile", like the original Vim logo

[type-anatomy]: See [LetterParts.com](https://letterparts.com/)'s interactive
    type anatomy

## LICENSE

Released under the [MIT license](LICENSE).

Vim and [`vimlogo.svg`](https://github.com/vim/vim/blob/master/runtime/vimlogo.svg)
are licensed under the [Vim license](https://github.com/vim/vim/blob/master/LICENSE).
(See also: [originals/vimlogo/](originals/vimlogo/README.md).)

`compass.svg` is licensed under the [MIT license](https://github.com/primefaces/primeicons/blob/master/LICENSE).
(See also: [originals/compass/](originals/compass/README.md).)
