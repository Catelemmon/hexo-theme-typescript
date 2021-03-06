# Hexo Theme Typescript

Typescript is a minimal theme for [Hexo](http://hexo.io).

This theme is also available on:

* Ghost version: [ghost-theme-typescript](https://github.com/artchen/ghost-theme-typescript)

## Dependencies

This theme depends on the following Hexo plugins to work correctly:

* hexo-generator-tag
* hexo-renderer-ejs
* hexo-renderer-less
* hexo-renderer-marked
* hexo-pagination

If you are to use local search instead of google custom search: 

* hexo-generator-json-content

and add the following to your global `_config.yml`:

```
# Generator json content
jsonContent:
  meta: false
  keywords: false
  pages:
    title: true
    slug: false
    date: false
    updated: false
    comments: false
    path: false
    link: false
    permalink: true
    excerpt: false
    keywords: false
    text: true
    raw: false
    content: false
  posts:
    title: true
    slug: false
    date: false
    updated: false
    comments: false
    path: false
    link: false
    permalink: true
    excerpt: false
    keywords: false
    text: true
    raw: false
    content: false
    categories: false
    tags: false
```

Please make sure these plugins are installed before generate the site.

## Customization

Typescript is customizable via `_config.yml` file under the theme directory.

The global `_config.yml` for Hexo may also need customization. In particular:

* Set `disqus_shortname` field to your disqus short name.
* Set `theme` field to `hexo-theme-typescript`.

In addition to these settings, users may also want to edit/replace the following files:

* Replace the site logo: `source/images/logo.png`, `source/images/logo.psd`
* The icon fonts are from [icomoon](https://icomoon.io/).
* The default English font is Futura PT via Adobe Typekit. If you are using Typekit like me, please change the embedded javascript code in `layout/_partial/head.ejs`, else you can delete the corresponding code.

This theme currently support 2 search services:

* Google Custom Search Engine: please fill in your api key and engine id in the `_config.yml` under the theme directory.
* Local search by querying `content.json` generated by [hexo-generator-json-content](https://github.com/alexbruno/hexo-generator-json-content). This is not recommended if you have a large number of posts.

## Demo

![Typescript Demo](http://artifact.me/images/ghost-theme-typescript-screenshot.png)

## Copyright

Public resources used in this theme:

* [icomoon](https://icomoon.io/)
* [normalize.css](https://necolas.github.io/normalize.css/)
* [fitvids.js](https://github.com/davatron5000/FitVids.js)

Copyright © Art Chen

Please do not remove the "Theme Typescript designed by Art Chen" text and links.

请不要删除页面底部的作者信息和链接。


