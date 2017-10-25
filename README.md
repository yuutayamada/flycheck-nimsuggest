# Flycheck-nimsuggest

A Flychek backend for Nim language using nimsuggest

## Manual Configuration

If you install this package from MELPA, probably this package
should work automatically, (if you followed nim-mode's instruction)
but if not, please use below manual configuration.

``` elisp
(add-hook 'nimsuggest-mode-hook 'flycheck-nimsuggest-setup)
```
