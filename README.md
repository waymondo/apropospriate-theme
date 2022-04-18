[![MELPA](http://melpa.org/packages/apropospriate-theme-badge.svg)](http://melpa.org/#/apropospriate-theme)
[![MELPA Stable](http://stable.melpa.org/packages/apropospriate-theme-badge.svg)](http://stable.melpa.org/#/apropospriate-theme)

## Apropospriate Theme ##

A colorful, low-contrast, light & dark theme set for Emacs 24.3+. It strives to be pleasant, clean, and consistent, with special focus for the current buffer.

This theme started as a Frakenstein mash-up of `base16-eighties-theme` and `solarized-light` themes which I customized heavily, then completely swapped out the color palette based on Google's [Material color suggestions](http://www.google.com/design/spec/style/color.html#color-color-palette).

### Screenshots ###

##### `apropospriate-dark-theme` #####

![](https://raw.github.com/waymondo/apropospriate-theme/master/dark.png)

##### `apropospriate-light-theme` #####

![](https://raw.github.com/waymondo/apropospriate-theme/master/light.png)

### Install & Usage ###

The recommended and easiest way to install is through [MELPA](http://melpa.org) via `package.el`:

```
M-x package-install apropospriate-theme
```

Or you can always manually download the directory somewhere and add it both `load-path` and `custom-theme-load-path`.

Once installed, load either theme variant with `M-x load-theme` or in your config:

``` elisp
(require 'apropospriate)
(load-theme 'apropospriate-dark t)
;; or
(load-theme 'apropospriate-light t)
```

[`use-package`](https://github.com/jwiegley/use-package) style:

``` elisp
(use-package apropospriate-theme
  :ensure t
  :config 
  (load-theme 'apropospriate-dark t)
  ;; or
  (load-theme 'apropospriate-light t))
```

### Supported Packages ###

Apropospriate supports all the usual `prog-mode` derived packages as well as some fun extra stuff:

* Company Mode
* Magit 1.x & 2.x
* Powerline
* Spaceline
* Rainbow Delimiters
* Highlight Blocks Mode
* Highlight Tail Mode
* Highlight Indent Guides Mode
* Highlight Indentation Mode
* Beacon
* Flycheck
* Flycheck Inline
* Flymake
* Auto Dim Other Buffers
* Ace Jump Mode
* Ace Jump Window
* Ace Jump Buffer
* Avy
* Swoop & Helm Swoop
* Highlight Symbol Mode
* Git Gutter
* Diff Hl (looks best with `diff-hl-margin-mode`)
* Pulse
* Helm
* Helm CSS SCSS
* Popup & Pos Tip
* Evil
* Tabbar
* Org Mode
* Guide Key
* Which Key
* Visible Mark
* ERC
* ORG
* Aznu
* Wgrep
* Eshell
* Ansi-Term
* Neotree
* Hydra
* Dired Subtree
* Dirvish
* Symbol Overlay
* Counsel CSS
* Ivy Posframe
* Smerge
* Lsp-mode
* Lsp-UI-mode
* Grizzl
* Hi-Lock
* Flyspell
* Display Numbers Line Mode
* Visual-Regexp
* Solaire
* Frog Menu
* Which Key Posframe
* Company Posframe
* Goggles
* Orderless
* Corfu
* Vertico
* Ediff
* Mlscroll
* Vertico Quick
* Tab-bar
* Tab-line
* VC-Annotate
* Window Divider Mode
* Transient
* Transient Posframe Mode
* Vertico Posframe Mode
* Tempel
