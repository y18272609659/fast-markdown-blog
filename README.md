# fast-markdown-blog

Fast build Markdown-Blog based on Nuxt. Just drag a `.md` file into the project and enter command, then the file is read automatically to generate a page. 
> 基于Nuxt快速搭建Markdown博客，只需拖入.md文件，输入命令行后自动读取，生成文章。

## Be Based On

`Nuxt` `nodejs` `frontmatter-markdown-loader`

## File List

```js
- articles
  |- article // 文件夹-放置.md文件
  |- list.js // 生成的文章信息列表

- pages
  |- index.vue // 博客首页
  |- blog
      |- _title.vue // 文章内容页
- server
    |- index..js // 读取写入操作
```

## Update list

$ npm run start (热加载 hot-load)
or
$ npm run dev

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
