[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/flymake-eask.svg)](https://jcs-emacs.github.io/jcs-elpa/#/flymake-eask)
<a href="#"><img align="right" src="https://raw.githubusercontent.com/emacs-eask/cli/master/docs/static/logo.png" width="20%"></a>

# flymake-eask
> Eask support in Flymake

[![CI](https://github.com/flymake/flymake-eask/actions/workflows/test.yml/badge.svg)](https://github.com/flymake/flymake-eask/actions/workflows/test.yml)

## 💾 Installation

In your `Eask` file:

```elisp
(source "gnu")
(source "melpa")
(source "jcs-elpa")

(depends-on "flymake-eask")
```

In your `init.el`:

```elisp
(require 'flymake-eask)
(add-hook 'eask-mode-hook 'flymake-eask-load)
```

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
