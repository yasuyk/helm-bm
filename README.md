# helm-bm.el [![licence][gplv3-badge]][gplv3-link] [![melpa badge][melpa-badge]][melpa-link] [![melpa stable badge][melpa-stable-badge]][melpa-stable-link]

[helm] sources for [bm.el][bm].

## Requirements

- [helm]
- [bm]
- [cl-lib]
- [s]

## Installation

If you're an Emacs 24 user or you have a recent version of package.el
you can install `helm-bm.el` from the [MELPA](http://melpa.milkbox.net/) repository.

## Configuration

Add the following to your emacs init file.

    (require 'helm-bm) ;; Not necessary if using ELPA package
    (global-set-key (kbd "C-c b") 'helm-bm)


## Basic usage

#### <kbd>M-x</kbd> `helm-bm`

Show bookmarks of [bm].el with `helm`.


[helm]:https://github.com/emacs-helm/helm
[bm]:https://github.com/joodland/bm
[cl-lib]:http://elpa.gnu.org/packages/cl-lib.html
[s]:https://github.com/magnars/s.el
[travis-badge]: https://travis-ci.org/yasuyk/helm-bm.svg
[travis-link]: https://travis-ci.org/yasuyk/helm-bm
[melpa-link]: http://melpa.org/#/helm-bm
[melpa-stable-link]: http://stable.melpa.org/#/helm-bm
[melpa-badge]: http://melpa.org/packages/helm-bm-badge.svg
[melpa-stable-badge]: http://stable.melpa.org/packages/helm-bm-badge.svg
[gplv3-badge]:http://img.shields.io/badge/license-GPLv3-blue.svg
[gplv3-link]:https://www.gnu.org/copyleft/gpl.html
