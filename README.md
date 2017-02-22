# Minos

**_A simple and retro styled theme, concentrated more on your ideas._**

Minos is a Hugo theme ported from Hexo theme [Minos](https://github.com/ppoffice/hexo-theme-minos). Requires Hugo v0.15+.

## Features

* Everything in the original Mino theme, except
    * Gallery (fancybox)
    * Duoshuo comment
    * Search box
    * Hierarchical categories (since this isn't supported in Hugo)
* Disqus
* Google Analytics
* [KaTeX](https://github.com/Khan/KaTeX)
* no jQuery :)

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

Licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
