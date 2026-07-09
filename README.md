[![Build Status](https://circleci.com/gh/devtools/vue_starter.svg?branch=main)](https://circleci.com/gh/devtools/vue_starter)

![img](https://avatars2.githubusercontent.com/u/6128107?v=4&s=140)
# Vue starter - application template | boilerplate

>  [Vue starter](https://github.com/devtools/vue_starter) is application template for rapid development. Built with [Vite](https://vitejs.dev/), [Pnpm](https://pnpm.io/), [Less](http://lesscss.org/), [Vue 3](https://vuejs.org/). Accelerates project kickoff with industry standards.

- Auto compilation via [Vite](https://vitejs.dev)
- Live reload on file modifications [vite-plugin-reload](https://github.com/antfu/vite-plugin-reload)
- Fast Refresh [vite-hmr](https://github.com/vitejs/vite-plugin-hmr)
- Native [Vue 3](https://vuejs.org/) support
- Auto preprocessing [Less](http://lesscss.org/) stylesheets
- Component testing via [vitest](https://github.com/vitest-dev/vitest)

## Getting started

### Files structure
```
├── /src/                       # Application source code
│   ├── /static/                # Static assets copied to dist
│   │   ├── /img/               # Image assets
│   │   ├── /typography/        # Font files
│   │   ├── icon.svg            # App icon
│   │   └── App.vue             # Root component
│   ├── /scripts/               # JavaScript modules
│   │   └── main.js             # Application entry
│   └── /styles/                # Stylesheet modules
│       ├── /core/              # Foundation styles
│       │   ├── typography.less # Font configuration
│       │   ├── utils.less      # Utility mixins
│       │   ├── vendor.less     # Third-party overrides
│       ├── /views/             # Component-specific styles
│       └── main.less           # Stylesheet entry
│
├── /dist/                      # Vite compiled output
│   ├── /img/                   # Processed images
│   ├── /js/                    # Bundled scripts
│   │   ├── vendor.js           # Third-party bundle
│   │   └── app.js              # Application bundle
│   ├── /css/                   # Compiled styles
│   │   └── main.css            # Main stylesheet
│   ├── icon.svg                # App icon
│   └── app.html                # Generated HTML
│
├── /spec/                      # Component test suites
│   ├── setup.js                # Test configuration
│   ├── Suite.spec.js           # Test cases
│   └── package.json            # Test dependencies
│
├── /documentation/             # Project documentation
├── /vue-cache/                 # Vue compiler artifacts
├── /node_modules/              # Pnpm dependencies
│
│── package.json                # Pnpm package manifest
│── vite.config.js              # Vite configuration
│── README.md                   # Project overview
│── LICENSE                     # License details
│── .editorconfig               # Editor settings
└── .gitignore                  # Git exclusions
```

> Vite generates `*.js.map` files for debugging.

### Commands

 `pnpm dev` - Launch development server

 `pnpm dist` - Generate production build

 `pnpm spec` - Execute test suite (vitest wrapper)

## Requirements

Install [Node](https://nodejs.org/en/), [Pnpm](https://pnpm.io/);

## Installation

`git clone https://github.com/devtools/vue_starter`

`cd vue_starter`

`pnpm install`

`pnpm dev`

# License

### This code is free to use under the terms of the MIT license.

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
