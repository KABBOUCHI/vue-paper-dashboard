# vue-admin-paper-dashboard

> Admin dashboard based on paper dashboard UI template + vue-router + vuex

This project is a vue version of [Paper-dashboard](https://www.creative-tim.com/product/paper-dashboard)
designed for vue js.The dashboard includes vue-router and vuex

Live [DEMO](https://cristijora.github.io/vue-paper-dashboard)

![](http://i.imgur.com/3iC1hOs.gif)

Note: Work in Progress on the unchecked parts from the TODO list
## Todo
* [ ] Implement all components in Vue
  * [x] Sidebar
  * [x] Charts
  * [x] Form
  * [x] Tables
  * [x] Custom Vue Notifications (WIP on notification layout)
* [ ] Add docs regarding implementation details
* [x] Cleanup vuex implementantion
* [x] Unit tests for custom components

## Build Setup

### install dependencies
`npm install`
### serve with hot reload at localhost:8080
`npm run dev`
### build for production with minification
`npm run build`
### run unit tests
`npm run unit`
### run and watch unit tests
`npm run unit:watch`

## Contribution guide
* `npm install` or `yarn install`
* If you use 3rd party libraries/components in more than 1 place make sure to define them globally for ease of use
  Example
  ```js
  Object.defineProperty(Vue.prototype, '$Chartist', {
    get() {
      return Chartist;
    }
  });
  ```
* Please don't use jQuery or jQuery based plugins since there are many pure Vue alternatives  
* Write unit tests for your custom components. See fgInput.spec and paper-table.spec

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
