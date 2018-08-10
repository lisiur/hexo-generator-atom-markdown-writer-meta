hexo-generator-atom-markdown-writer-meta-fixed-fixed [![NPM version][npm-image]][npm-url] [![Dependency Status][depstat-image]][depstat-url]
========================================

> A [Hexo][hexo-url] generator that produces meta json files required by the [Atom][atom-url] [Markdown-Writer][markdown-writer-url]
> It generates `posts.json`, `categories.json` and `tags.json` under the root site.

## Install

Install using [npm][npm-url].

    $ npm install hexo-generator-atom-markdown-writer-meta-fixed-fixed --save

## Markdown-Writer Configuration for Hexo

Field          | Sample Value
---------------|----
File Extension | .md
Site Draft Dir | source/_drafts
Site Local Dir | /Users/youngjuning/Workspace/blogs/youngjuning
Site Posts Dir | source/_posts
Url for Categories | http://youngjuning.github.io/categories.json
Url for Posts      | http://youngjuning.github.io/posts.json
Url for Tags       | http://youngjuning.github.io/tags.json

## Files

* `posts.json`: Json file contains name, url and last update time for each post
* `tags.json`: Json file contains the tags that used in the blog, sorted by occurrence
* `cateogories.json`: Json file contains the categories that used in the blog, sorted by occurrence

## Related Tools

* [ATOM Editor][atom-url]
* [Markdown-Writer][markdown-writer-url]
* [Hexo][hexo-url]

## License
MIT

[![NPM downloads][npm-downloads]][npm-url]

[homepage]: https://github.com/youngjuning/hexo-generator-atom-markdown-writer-meta-fixed

[npm-url]: https://npmjs.org/package/hexo-generator-atom-markdown-writer-meta-fixed
[npm-image]: http://img.shields.io/npm/v/hexo-generator-atom-markdown-writer-meta-fixed.svg?style=flat
[npm-downloads]: http://img.shields.io/npm/dm/hexo-generator-atom-markdown-writer-meta-fixed.svg?style=flat

[depstat-url]: https://gemnasium.com/youngjuning/hexo-generator-atom-markdown-writer-meta-fixed
[depstat-image]: http://img.shields.io/gemnasium/youngjuning/hexo-generator-atom-markdown-writer-meta-fixed.svg?style=flat

[atom-url]: https://atom.io/
[markdown-writer-url]: https://github.com/zhuochun/md-writer
[hexo-url]: http://hexo.io/
