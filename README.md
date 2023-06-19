# paopao-video-player
____

![VueJS](https://img.shields.io/badge/vuejs-%2335495e.svg?&style=for-the-badge&logo=vue.js&logoColor=%234FC08D)  ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?&style=for-the-badge&logo=tailwind-css&logoColor=white)

[![NPM](https://nodei.co/npm/paopao-video-player.png)](https://nodei.co/npm/paopao-video-player/)

A modern, visual video player for Vue3.
It will bring your videos to life with a customizable and powerful player!


### Install
```js
npm install paopao-video-player
```

### Global
```js
import Vue from 'vue'
import PaoPaoVideoPlayer from 'paopao-video-player'

Vue.use(PaoPaoVideoPlayer, /* { default options with global component } */)
```

### Local registration
```js
import PaoPaoVideoPlayer from 'paopao-video-player'

export default {
  components: {
    PaoPaoVideoPlayer
  }
}
```

____

## Props
| Name   |      Type      |  Default | Description |
|----------|:-------------:|------:|------:|
| src |  string | required |  Source file |
| autoplay |    boolean   |   false |  Video played when component is load |
| loop | boolean |   false | Play the video again |
| controls | boolean |   true | Display controls |
| mask | boolean |   true | Display the mask on first load |
| hoverable | boolean |   true | Display the controls at the hover |
| colors | String, Array |   ['#fbbf24', '#ec4899'] | Change colors components |
| theme | String |   basic | You can change theme of component: basic, gradient |