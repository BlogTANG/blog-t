# BlogT

[![License](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](LICENSE)

This is a collection of themes for [BlogA](https://github.com/BlogTANG/blog-a).

## How To Use

First, clone the theme repo to your local.

```sh
cd blog-a/themes
git clone https://github.com/BlogTANG/blog-t -b branch-name theme-name
```

The `branch-name` here is the branch which contains the theme you want, and `theme-name` is your local theme name. You can just make them the same.

Then, configure the `config.py`'s `theme` property, make it the theme name you want to use, and run the following command to apply the change:

```py
python app.py apply-theme
```

After all the above, you can now run your own BlogA instance with your favourite theme.

## Theme Table

| Theme | Preview | Notes |
| ----- | ------- | ----- |
| [default]   | [Preview][default-preview]      | Clean and modern.
| [classic]   | [Screenshot][classic-preview]   | Minimal GitHub Issues style.
| [fenki]     | [Screenshot][fenki-preview]     | A clean theme for using as wiki.

[default]: https://github.com/BlogTANG/blog-t/tree/default
[classic]: https://github.com/BlogTANG/blog-t/tree/classic
[fenki]: https://github.com/BlogTANG/blog-t/tree/fenki
[default-preview]: http://blog-a.demo.r-c.im/
[classic-preview]: https://raw.githubusercontent.com/BlogTANG/blog-t/classic/screenshot.jpg
[fenki-preview]: https://raw.githubusercontent.com/BlogTANG/blog-t/fenki/screenshot.jpg
