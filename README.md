[toc]

## Introduction
This is a customized hexo-fluid theme that features a concise and well-organized style. You can view it [here](https://david-qm.netlify.app/). And you can view the original theme [here](https://hexo.fluid-dev.com/).  

To enhance the user experience and provide a more systematic display of content, I made some minor modifications to the original theme.  

## Modifications 
- **Header of pages**
Implemented the use of secondary categories for better content organization while maintaining conciseness. 
[*You can directly configure this in the hexo-fluid-theme `config.fluid.yml` file.*]
- **Picture in the top of pages**
Reduced image height to ensure that readers focus more on the content of the post(excluding the index page).
[*You can directly configure this in the hexo-fluid-theme `config.fluid.yml` file.*]
- **The index page**
  1.Removed all posts from the bottom of the page.
  2.Added the content of the "about" page to this page and disable the "about" page.
  3.Included a more detailed self-introduction post below the about content.
  [*Made changes in the file `index.ejs`*]
- **The news page**
  1.Added a dedicated page to showcase important news.
  2.Organized and displayed all news based on the posting date.
  [*Created the file `news.ejs`*]
- **The other pages** 
  1.Added pages for secondary categories.
  2.Displayed the content of each secondary category.
  [*Created the file `second_categories.ejs`*]


## Version
- **hexo**
```
    hexo-cli: 4.3.1
    os: win32 10.0.19045
    node: 20.7.0
    acorn: 8.10.0
    ada: 2.6.0
    ares: 1.19.1
    base64: 0.5.0
    brotli: 1.0.9
    cjs_module_lexer: 1.2.2
    cldr: 43.1
    icu: 73.2
    llhttp: 8.1.1
    modules: 115
    napi: 9
    nghttp2: 1.55.1
    nghttp3: 0.7.0
    ngtcp2: 0.8.1
    openssl: 3.0.10+quic
    simdutf: 3.2.17
    tz: 2023c
    undici: 5.23.0
    unicode: 15.0
    uv: 1.46.0
    uvwasi: 0.0.18
    v8: 11.3.244.8-node.15
    zlib: 1.2.13.1-motley
```
- **Hexo-fluid-theme**
    `hexo-theme-fluid@1.9.5-a`
## Documentation 
You may find the following documentation helpful:
- [hexo](https://hexo.io/)
- [hexo-fluid-theme](https://fluid-dev.github.io/hexo-fluid-docs/)

I would like to express my gratitude to the teams behind hexo and hexo-fluid-theme for their excellent work. If you are interested, please consider contributing or donating to support them.
