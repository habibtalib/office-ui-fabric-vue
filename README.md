# Office UI Fabric Vue

## Introduction

Office UI Fabric implementation for Vue.js, build with [office-ui-fabric-js](https://github.com/OfficeDev/office-ui-fabric-js)

## Installation

```
  $ yarn add office-ui-fabric-vue
  // or
  $ npm install office-ui-fabric-vue
```

## Usage


```javascript
  import Vue from 'vue'
  import OfficeUIFabricVue from 'office-ui-fabric-vue';

  // import css style
  import 'office-ui-fabric-vue/dist/index.css';

  Vue.use(OfficeUIFabricVue);
```

## Development

```
// clone the repo

$ git clone https://github.com/aidewoode/office-ui-fabric-vue.git

// install all dependencies

$ yarn install

// runing the doc site

$ yarn run server

// bundle the file

$ yarn run bundle

```


## Notice

This project just include js components, for the basic styling, include the icons, colors, layout, typography..., you can check the [Fabric Core](https://github.com/OfficeDev/office-ui-fabric-core) project.

This project already include Jquery and PickaDate, and used for the DatePicker component.

This project still in early stage, so the api of this components may have some break change later. If you find bugs or have feature quest, please [add a new issue](https://github.com/aidewoode/office-ui-fabric-vue/issues).
