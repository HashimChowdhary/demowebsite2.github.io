# Digital Scotland Design System Pattern Library

This pattern library contains all the code needed to start building user interfaces for websites and web applications for the Scottish Government and other Scottish public sector bodies.

See live examples of the available components, alongside guidance on how and when to use them in the [Digital Scotland Design System](https://designsystem.gov.scot/).

## Feedback, help or support

If you need any help or want to give any feedback you can e-mail the Design System team at: [designsystem@gov.scot](mailto:designsystem@gov.scot).

## How to start using the Design System in your project

We recommend using npm to install the Design System and compiling the CSS from the source (https://designsystem.gov.scot/get-started/installation/)

### project setup
```
npm install
```
### Compiles and hot-reloads for development
```
npm run sass-dev
```
### Compiles and minifies for production
```
npm run sass-prod
```
## Our project’s folder structure:
project/
├── assets/
│   ├── css/
│   │   └── style.css
│   └── scss/
│       ├── _footer.scss/
│       ├── _header.scss
│       ├── _main.scss
│       └── style.scss
├── node-modules/
└── package.json

## Customize setting
See [Configuration Reference](https://sprucecss.com/blog/the-simplest-sass-compile-setup)