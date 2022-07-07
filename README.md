# vue2-bootstrap
vue create vue2-bootstrap

cd vue2-bootstrap

https://www.digitalocean.com/community/tutorials/vuejs-using-bootstrap4

npm install --save @popperjs/core

npm install bootstrap@4.6.0 bootstrap-vue@2.21.2

## Edit main.js
```
import Vue from 'vue'
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'
import App from './App.vue'

import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

Vue.config.productionTip = false

Vue.use(BootstrapVue)
Vue.use(IconsPlugin)

new Vue({
  render: h => h(App),
}).$mount('#app')
```

vue add router

vue add electron-builder

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
