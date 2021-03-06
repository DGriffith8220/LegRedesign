<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/assets/brand/bootstrap-solid.svg" alt="" width=72 height=72>
  </a>

  <h3 align="center">LNET Redesign - Bootstrap</h3>

  <p align="center">
    Sleek, intuitive, and powerful front-end framework for faster and easier web development.
    <br>
    <a href="https://getbootstrap.com/docs/4.0/"><strong>Explore Bootstrap docs »</strong></a>
    <br>
    <a href="https://sass-lang.com/guide">Explore SASS »</a>
  </p>
</p>

<br>

## Table of contents

- [Quick start](#quick-start)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Contributing](#contributing)


## Quick start

Set up dependencies and get to work:

- Windows Users Install [RubyInstaller](https://rubyinstaller.org/): Gives you [gem](http://guides.rubygems.org/rubygems-basics/)
- Linux Users Install [Ruby Version Manager](https://rubyinstaller.org/): Gives you [gem](http://guides.rubygems.org/rubygems-basics/)
- Install Sass with gem: `gem install sass`
- Install [nodeJS](https://nodejs.org/en/): Gives you Node Package Manager [(npm)](https://docs.npmjs.com/) 
    - If creating a new Bootstrap project (our source files are already setup): 
        - Install bootstrap: `npm install bootstrap`
        - Install font-awesome: `npm install font-awesome`
        - Install jquery: `npm install jquery`
        - Install roboto-fontface: `npm install roboto-fontface`
    - If adding new images to img/banners/: `node js/dirs.js`
- Clone the repo: `git clone https://github.com/LegislativeCoordinatingCommissionGIS/2018_design.git`
- Watch and compile Sass: `sass -watch styles/scss:styles/css`
    - Sass watches for .scss changes in `styles/scss` folder and compiles to .css in `styles/css` folder

Read the [Sass](https://sass-lang.com/install) and [Bootstrap](http://getbootstrap.com/docs/4.0/getting-started/download/) documentation for information on the framework and more.


## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
2018_design/
├── html/
│   ├── docs/
│   │   ├── banner.html
│   │   ├── components.html
│   │   ├── grid.html
│   │   ├── lcc.html
│   │   └── test.html
│   ├── house/
│   │   └── index.html
│   ├── joint/
│   │   └── index.html
│   └── senate/
│       └── index.html
│
├── styles/
│   ├── css/
│   │   ├── app.css
│   │   ├── app.css.map
│   │   ├── jquery-ui.css
│   │   └── jquery-ui.css.map
│   │
│   ├── fonts/
│   │
│   └── scss/
│       ├── _lnet.scss
│       ├── _lnet-datepicker.scss
│       ├── _lnet-footer.scss
│       ├── _lnet-mixins.scss
│       ├── _lnet-navbar.scss
│       ├── _variables.scss
│       ├── app.scss
│       ├── jquery-ui
│       └── jquery-ui.scss
├── img/
│   └── banners/
│
├── js/
│   ├── jquery-ui.1.12.1.custom/
│   │   └── jquery-ui assets
│   ├── bootstrapWindowHelper.js
│   ├── calendar.js
│   ├── dirs.js
│   ├── docsApp.js
│   ├── getParameterByName.js
│   └── navbarhelper.js
│
└── node_modules/
    ├── bootstrap/
    ├── font-awesome/
    ├── jquery/
    ├── roboto-fontface/
    └── readme.txt

```

We will provide compiled CSS and JS (`app.*`), as well as compiled and minified CSS and JS (`app.min.*`). CSS [source maps](https://developers.google.com/web/tools/chrome-devtools/debug/readability/source-maps) (`app.css.map`) are available for use with certain browsers' developer tools.


## Contributing

**Do not edit `/styles/css/app.css` or  `node_modules/bootstrap/` directly!** Those files are automatically generated. You should edit the
source files in [`/styles/scss/`](https://github.com/LegislativeCoordinatingCommissionGIS/2018_design/tree/master/styles/scss)
and/or [`js/`](https://github.com/LegislativeCoordinatingCommissionGIS/2018_design/tree/master/js) instead.

The [GitLab issue tracker](hhttp://gitrh01.revisor.mn.gov/legislature/2018_design/issues) or [GitHub](https://github.com/LegislativeCoordinatingCommissionGIS/2018_design/issues)  is the preferred channel for bugs, feature requests, and submitting pull requests

All HTML and CSS should conform <i>(generally)</i> to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).