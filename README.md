## Apropospriate Theme ##

A colorful, low-contrast, light & dark theme set for Emacs. It strives to be pleasant, clean, and consistent, with special focus for the current buffer.

This theme started as a Frakenstein mash-up of `base16-eighties-theme` and `solarized-light` themes which I customized heavily, then completely swapped out the color palette based on Google's [Material color suggestions](http://www.google.com/design/spec/style/color.html#color-color-palette).

### Screenshots ###

![](https://raw.github.com/waymondo/apropospriate-theme/master/dark.png)
![](https://raw.github.com/waymondo/apropospriate-theme/master/light.png)

### Install & Usage ###

Download the directory somewhere and add it both `load-path` and `custom-theme-load-path`.

<!-- You can always download and add it to your load path manually, but the easiest way to install is through [MELPA](http://melpa.org) via `package.el`: -->

<!-- ``` -->
<!-- M-x package-install apropospriate-theme -->
<!-- ``` -->

Once installed, load either theme with `M-x load-theme` or in your config:

``` elisp
(load-theme 'apropospriate-dark t)
;; or
(load-theme 'apropospriate-light t)
```

### Supported Packages ###

Apropospriate supports all the usual `prog-mode` derived packages as well as some fun extra stuff:

* Company Mode
* Magit (as well as the `next` branch for the upcoming 2.0 release)
* Powerline
* Rainbow Delimiters
* Highlight Tail Mode
* Auto Dim Other Buffers
* Ace Jump Mode (and related extensions)
* Swoop & Helm Swoop
* Highlight Symbol Mode
* Git Gutter and Diff Hl Modes
* Pulse
* Popup & Pos Tip
* Evil's cursors
* Tabbar
* Org Mode
