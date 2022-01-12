# Vue 3 - Products and Cart App

## What is this about?

Demo of a website that contains products you can add and delete off of a cart.</br>
</br>
It's a code-along to freecodecamp's free course, see YouTube video [Vue.js Course for Beginners [2021 Tutorial]](https://www.youtube.com/watch?v=FXpIoQ_rT_c).</br>
### Visuals
![home01](./screenshots/home01.png)
![home02](./screenshots/home02.png)
![products01](./screenshots/products01.png)
![pastorders01](./screenshots/pastorders01.png)

- the code you see in my project is **not** built from scratch by me, it already came with HTML and CSS
- my code is based on [the tutorial branch/code "home-page-1"](https://github.com/gwenf/vue3-fcc-course-basic-product-cart-demo/tree/home-page-1), then coded along further until the final result
- I did not clone the `starter-code` branch of the tutorial repository, but the `home-page-1`
- if you are interested in the final result solved by the tutor, [see their final branch "4-reusable-components" here](https://github.com/gwenf/vue3-fcc-course-vue-cli-product-cart-demo/tree/4-reusable-components)
- in my example at point of writing this `README`, the "Past Products" page is still static
- products come in via `.json`, not via `fetch`

### How to run it?
- clone the repo
- cd into project `products-and-cart-app`
- run `npm install`
- run `npm run serve`, this will fire up the server at
```
 App running at:
  - Local:   http://localhost:8080/
  - Network: http://192.168.178.53:8080/
```
- stop the server with `control c`
- run `npm run build`, to compile and minify for production
- run `npm run lint`, to lint and fix files

### Nice to know - Steps towards product app

The freecodecamp YouTube tutorial https://www.youtube.com/watch?v=FXpIoQ_rT_c provides a great step by step Vue 3 learning, starting with the most basic code.</br>

**Up to 1:14:31**
- it's working on Basic Vue Examples in single html files, to get familar with Vue
- Vue comes in via CDN, see `<script src="https://unpkg.com/vue@next"></script>` tag, also see here https://v3.vuejs.org/guide/installation.html#release-notes
- find the basic code-along examples here: [Intro into Vue - Basic Vue 3 Examples](https://github.com/EllyPirelly/products-and-cart-app/tree/main/steps-towards-app/intro-into-vue)

**From 1:14:31 to 2:15**
- it's about having the (given) Products and Cart App code in a Vue 3 environment, clearing the path of understanding how everything works in a context of Vue 3
- Vue 3 comes in via CDN, see `<script src="https://unpkg.com/vue@next"></script>` tag
- as everything is based on importing Vue via CDN `<script src="https://unpkg.com/vue@next"></script>` this keeps us of going full dynamic as we now would have to make data persistable via localstorage to not change the cart while changing the page (this would be the point in time to introduce Vue CLI)
- **I decided to not keep this part of code-along code**

**From 2:26 on**
- it's introducing Vue CLI and making the (given) Products and Cart App code more dynamic

### These are the sources of the tutor
- [Static files from initial lessons](https://github.com/gwenf/vue3-fcc-course-static-code)
- [Product and Cart Static Code Demo](https://github.com/gwenf/vue3-fcc-course-basic-product-cart-demo)
- [Product and Cart Vue CLI Demo](https://github.com/gwenf/vue3-fcc-course-vue-cli-product-cart-demo)

### Install Vue CLI

- https://cli.vuejs.org/guide/installation.html
- run `npm install -g @vue/cli`
- version at time of writing `@vue/cli 4.5.15`

### Create a Vue Project

 - https://cli.vuejs.org/guide/creating-a-project.html
 - run `vue create YOUR-PROJECT-NAME`

```
   App running at:
  - Local:   http://localhost:8080/
  - Network: http://192.168.178.53:8080/
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/)

### How to work with scss

- https://cli.vuejs.org/guide/css.html
- `npm install -D sass-loader@^10 sass`
