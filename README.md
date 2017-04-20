# Minos

**_A simple and retro styled theme, concentrated more on your ideas._**

Minos is a Hugo theme ported from Hexo theme [Minos](https://github.com/ppoffice/hexo-theme-minos). Requires Hugo v0.20+.

## Screenshots

![Home](https://cdn.rawgit.com/carsonip/hugo-theme-minos/cb2cdd88/images/screenshot.png)
![Article](https://cdn.rawgit.com/carsonip/hugo-theme-minos/cb2cdd88/images/article.png)
![Tag](https://cdn.rawgit.com/carsonip/hugo-theme-minos/cb2cdd88/images/tag.png)

## Features

* Everything in the original Mino theme, except
    * Gallery (fancybox)
    * Duoshuo comment
    * Search box
    * Hierarchical categories (since this isn't supported in Hugo)
* Smart table of contents (will highlight and expand current section in TOC)
* Disqus
* Google Analytics
* [KaTeX](https://github.com/Khan/KaTeX)
* Syntax highlighting using [highlight.js](https://github.com/isagalaev/highlight.js)

## Installation

To install Minos as your theme, first clone this repository in the `themes/` directory:

```
$ cd themes/
$ git clone --depth 1 https://github.com/carsonip/hugo-theme-minos
```

Second, specify `hugo-theme-minos` as your default theme in the config.toml file. Just add the line

```
theme = "hugo-theme-minos"
```

## Options

### Smart TOC
```
[params]
    smartToc = true
```

### Disqus
```
[params]
    disqusShortname = "xxxxxx"
```

### Google Analytics
```
[params]
    googleAnalytics = "UA-123-45"
```

### KaTeX
```
[params]
    katex = true
```

## Post Params

### Featured Image displayed in index.html
```
+++
featuredImage = "img/foobar.jpg"
+++
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Original Author

PPOffice

* https://github.com/ppoffice

## Ported by

Carson Ip

* https://github.com/carsonip

## License

Licensed under the MIT License. See the [LICENSE](https://github.com/carsonip/hugo-theme-minos/blob/master/LICENSE.md) file for more details.
