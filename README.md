<a href="https://www.patreon.com/sanityinc"><img alt="Support me" src="https://img.shields.io/badge/Support%20Me-%F0%9F%92%97-ff69b4.svg"></a>

paredit-everywhere.el
=====================

It turns out that a lot of the `paredit` key bindings work as
expected in non-lisp buffers, since many major modes provide
reasonable sexp-oriented navigation.

This library, then, provides a minor mode which enables a subset
of the `paredit` library's editing commands in non-lisp buffers.

A grander project offering similar functionality is Matus Goljer's
[smartparens package](https://github.com/Fuco1/smartparens).

Installation
=============

If you choose not to use one of the convenient packages in
[MELPA][melpa], you'll need to add the
directory containing `paredit-everywhere.el` to your `load-path`, and then
`(require 'paredit-everywhere)`.

Usage
=====

Enable the minor mode in non-lisp buffers by adding `paredit-everywhere-mode` to
your mode hooks. In Emacs 24 and greater, `prog-mode-hook` is a great choice:

```elisp
(add-hook 'prog-mode-hook 'paredit-everywhere-mode)
```

Use <kbd>C-h m</kbd> to see which paredit commands are available.

[melpa]: http://melpa.org

<hr>

[💝 Support this project and my other Open Source work via Patreon](https://www.patreon.com/sanityinc)

[💼 LinkedIn profile](https://uk.linkedin.com/in/stevepurcell)

[✍ sanityinc.com](http://www.sanityinc.com/)

