# Contentful blog

>A simple blog using Contentful to manage content!

## Live Demo
Coming Soon

## Getting Started
I forked this repo from [blog-in-5-minutes](https://github.com/contentful/blog-in-5-minutes) so head over [here](https://github.com/contentful/blog-in-5-minutes/blob/master/docs/GETTING-STARTED.md) to get set up.

## Deploy

### Preview Site Locally

```bash
$ npm run dev
```
One of the big advantages of using Nuxt is that it comes with static site generation! Nuxt will go through the routes of our site and generate a dist folder containing purely static HMTL files which you can then use to host your site on any static site hosting service. 
To try this out, run nuxt generate and then use a simple http server like http-server to serve the generated dist folder. 

```bash
$ npm run generate
$ npm install -g http-server 
$ cd dist
$ http-server
```




