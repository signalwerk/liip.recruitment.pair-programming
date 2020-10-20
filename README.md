# Vue·Nuxt for Ueli

## ToDo's
* Why and what?
* Checkout → work in own Branch
* Install → Node Version, npm, yarn, lockfile
* [Nuxt](https://nuxtjs.org/)
* Start → Build, Start
* Coding Standard → prettier eslint
* What are components in Vue → Overview
  * Clean out Logo component & Buttons
  * Add Card as component
  * Filter Cards by age. only > 18
  * [Add SCSS](https://nuxtjs.org/faq/pre-processors/) → why?
  * `rem` → Setup media-query for `rem`-size



## Cards layout
```
cards                                                                                                                

┌─────────────────────────────────────────────────────────────────────────────────────────────────────────────────┐     
│                                                                                                                 │     
│                                                                                                                 │     
│                                                                                                                 │     
│  col-width: 23%              col-width: 23%              col-width: 23%              col-width: 23%             │     
│ ┌────────────────────────┐  ┌────────────────────────┐  ┌────────────────────────┐  ┌────────────────────────┐  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ └────────────────────────┘  └────────────────────────┘  └────────────────────────┘  └────────────────────────┘  │     
│                                                                                                                 │     
│ ┌────────────────────────┐  ┌────────────────────────┐  ┌────────────────────────┐  ┌────────────────────────┐  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ │                        │  │                        │  │                        │  │                        │  │     
│ └────────────────────────┘  └────────────────────────┘  └────────────────────────┘  └────────────────────────┘  │     
│                                                                                                                 │     
└─────────────────────────────────────────────────────────────────────────────────────────────────────────────────┘     
```


---


## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
