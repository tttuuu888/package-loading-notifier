# package-loading-notifier
[![MELPA](https://melpa.org/packages/package-loading-notifier-badge.svg)](https://melpa.org/#/package-loading-notifier)

`package-loading-notifier` notify when packages are loaded.

![demo](https://gist.githubusercontent.com/tttuuu888/267a8a56c207d725ea999e353646eec9/raw/b960dfcf9ac1e8c9330d9385368fcd4a2cfdc981/package-loading-notice.gif)

# Installation

`package-loading-notifier` can be installed through [MELPA](https://melpa.org).

# Configuration

## Global mode
To enable `package-loading-notifier`, add following in your `.emacs` file:

    (require 'package-loading-notifier)
    (package-loading-notifier-mode 1)

## Add more packages
To add more packages for `package-loading-notifier`, set `package-loading-notifier-packages` variable.

    (setq package-loading-notifier-packages '(org magit yasnippet))
