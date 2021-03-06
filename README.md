vim-apoklinon
=============

A dark 256 colour scheme for Vim

## Philosophy

From the Greek αποκλίνων, meaning divergent. A number of colourschemes out in the wild don't take any queues from colour theory; rather they mash a few colours together and hope for the best. Others certainly do take the time to generate a decent complimentary palette, but most seem to limit their options to only a few select colours rather than a large spread of possibilities. Apoklinon is an attempt at using the full range of the colour spectrum; whilst being tasteful, easy to read (and code) with, and also gives the user a slew of theming capability when porting to other projects.

## Requirements

This colourscheme is intended for use on:

-   Vim 7.3 for Linux and Mac, using a 256 colour enabled terminal.

-   gVim 7.3 for Linux, Mac and Windows.

By default, Vim will use the closest matching cterm equivalent of the RGB
colours.

## Recommended terminal colours

Due to the limited 256 palette, colours in Vim and gVim will still be slightly
different. In order to get the same colours as gVim and use this colourscheme
the way that it was intended, it is highly recommended that you:

1.  Add these colours to ~/.Xresources or ~/.Xdefaults:


2.  Use Xresources colours by setting in ~/.vimrc:

        let g:apoklinon_use_Xresources = 1
        colorscheme apoklinon

## Screenshots

Will put some up soon (when the scheme is ready)

## TODO

- [X] Get Xdefaults under wraps for terminal colours.
- [X] Shuffle less used colors to bold.
- [X] Rework monochrome gradient - probably too divergent, we can use most of these colours from the 256 palette, there's no need to fill Xdefaults with them. [Extended palette in general, but only use non 256 colours in Xdefaults] 
- [X] Realign colours [Initial pass, will work with it for a while to see if there's any useful improvements]
- [ ] Test Markup
- [ ] Test Haskell
- [ ] Test Ruby
- [ ] Test HTML
- [ ] Test CSS/SCSS/SASS
- [ ] Test Scala
- [ ] Test Bash/Zsh
- [ ] Test C/C++
- [ ] Test Matlab
- [ ] Test Latex



## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FLibbum%2Fvim-apoklinon.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FLibbum%2Fvim-apoklinon?ref=badge_large)
