# Vue 3 - Products and Cart App

## What is this about?

Demo of a website that contains products you can add and delete off a cart.</br>
Products come in via `.json`, not via `fetch`.</br>
A code-along to freecodecamp's free YouTube video [Vue.js Course for Beginners [2021 Tutorial]](https://www.youtube.com/watch?v=FXpIoQ_rT_c)</br>

- up to 1:14, it's working on basic code of the project in single html files
- from 1:14 to 2:15, it's about having the code in a more modular environment, but still without Vue
- from 2:26 on, it's introducing Vue cli and making the project more dynamic

### Visuals
![home01](./screenshots/home01.png)
![home02](./screenshots/home02.png)
![products01](./screenshots/products01.png)
![pastorders01](./screenshots/pastorders01.png)

The code you see in my project is not built from scratch.</br>
It is based on [this branch/code](https://github.com/gwenf/vue3-fcc-course-basic-product-cart-demo/tree/home-page-1), coded along until the final result, so it already came with HTML and styling.</br>
I did not clone the `starter-code` branch of that repository but the `home-page-1`.</br>
If you are interested in the final result solved by the tutor, [see their final branch here](https://github.com/gwenf/vue3-fcc-course-vue-cli-product-cart-demo/tree/4-reusable-components).</br>
In my example at point of writing the "Past Products" page ist still static.</br>

<!-- TODO:
add general learning as an extra branch
add static code demo as an extra branch
add descriptive READMEs to those branches
- first part of video shows general learnings about vue.js
- second important part of video: extract static content, bit by bit
- in both of those parts, everything's based on importing vue3 via CDN `<script src="https://unpkg.com/vue@next"></script>`, only in the dynamic part we npm installed vue -->

### These are the sources of the tutor
- [Static files from initial lessons](https://github.com/gwenf/vue3-fcc-course-static-code)
- [Product and Cart Static Code Demo](https://github.com/gwenf/vue3-fcc-course-basic-product-cart-demo)
- [Product and Cart Vue CLI Demo](https://github.com/gwenf/vue3-fcc-course-vue-cli-product-cart-demo)


### How to run this?
- clone the repo
- cd into project
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

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/)

### Nice to know

#### Install Vue CLI

- https://cli.vuejs.org/guide/installation.html
- run `npm install -g @vue/cli`
- version at time of wriing `@vue/cli 4.5.15`

#### Create a Vue Project

 - https://cli.vuejs.org/guide/creating-a-project.html
 - run `vue create YOUR-PROJECT-NAME`

```
   App running at:
  - Local:   http://localhost:8080/
  - Network: http://192.168.178.53:8080/
```

#### How to work with scss

- https://cli.vuejs.org/guide/css.html
- `npm install -D sass-loader@^10 sass`
