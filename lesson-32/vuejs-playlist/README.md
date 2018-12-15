# cli-project

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

<h2>Explanation of tutorial</h2>

Install new package vue-resource

npm install vue-resource --save

--save means it will save package dependency in the package.json file

Lesson already has this package in the package.json file so there's no need for above command.

Collected data will be sent to the "fake" url http://jsonplaceholder.typicode.com/posts which gives us a response (excellent for testing purposes).

Refer to the App.vue component to see how sending data via ajax can be performed using vue-resource plugin.
