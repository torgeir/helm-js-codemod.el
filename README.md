# helm-js-codemod.el
A helm interface for running js-codemods using [js-codemod.el](https://github.com/torgeir/js-codemod.el)

## Installing

It's on [MELPA](https://melpa.org/#/getting-started), so run `M-x package-install helm-js-codemod` to install it.

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



## License

Copyright (C) 2017 Torgeir Thoresen

Author: @torgeir

Keywords: helm js codemod region

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
