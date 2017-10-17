# helm-js-codemod.el
A helm interface for running js-codemods using [js-codemod.el](https://github.com/torgeir/js-codemod.el)

## Installing

It's soon™ on [MELPA](https://melpa.org/#/getting-started), so any minute now you can run `M-x package-install helm-js-codemod` to install it.

Or preferably using the ingenious [use-package](https://github.com/jwiegley/use-package) declaration

```
(use-package helm-js-codemod
  :commands (helm-js-codemod)
  :init
  (setq helm-js-codemod-mod-dir "path/to/codemods/"))
```

## Features

Run `helm-js-codemod` after selecting a region to run one your favorite js codemods on it, e.g. to [turn this bound functions into arrow functions](https://github.com/mikaelbr/vscodemod/blob/140f401415194772bbd42eaa37ac26f62909914e/codemods/to-arrow.js), like so

<img src="https://d3vv6lp55qjaqc.cloudfront.net/items/430N0P091V3W0d0l3N3M/Screen%20Recording%202017-10-17%20at%2010.02%20PM.gif?X-CloudApp-Visitor-Id=5102c944a369d2eb3e4cef97298683d9&v=ccc4964a" width="80%"/>
