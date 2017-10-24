# Flycheck-nimsuggest

A Flychek backend for Nim using nimsuggest

## Manual Configuration

If you install this package from MELPA, probably this package
should work automatically, but if not, please use below manual
configuration.

``` elisp
(add-hook 'nimsuggest-mode-hook 'flycheck-nimsuggest-setup)
```
