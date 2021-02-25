# HUGO HT

A simple hugo theme suitable for bilingual personal blogs. It is  a copy of [my personal website](https://hongtaoh.com/).

[Example site]()

## Shoulders of the giants

I wouldn't call it a "theme" because it is heavily built on other people's work:

- The base of Hugo-ht is [Yihui Xie](https://github.com/yihui)'s [hugo-xmin](https://github.com/yihui/hugo-xmin)

- The design of navigation bar and footer texts is copied from the theme of [Lithium](https://themes.gohugo.io/hugo-lithium-theme/) by Jonathan Rutheiser

- Styles of body texts are based on [typo.css](https://github.com/xiangming/typo/blob/master/css/typo.css) by [xiangming](https://github.com/xiangming)

- The style of table of contents is based on that of Zachary Betz's [personal blog](https://zwbetz.com/).

- Custom blocks are based on the [CSS of Bookdown](https://github.com/rstudio/bookdown/blob/master/inst/examples/css/style.css) by Yihui Xie

## Installation

Navigate to the root of hugo project and run:

```bash
cd themes
git clone https://github.com/hongtaoh/hugo-ht
git remote rm origin
cd ..
```

Or you can add hugo-ht as a submodule:

```bash
git submodule add https://github.com/hongtaoh/hugo-ht themes/hugo-ht
```

The difference between the two methods is that if you add it as a submodule, the `hugo-ht` theme you use is connected to this repository. The benefit is that you can keep it updated, but there is a caveat: if you make lots of changes to the styles based on your personal preferences, these changes might be lost.

If you pretty satisfied with what `hugo-ht` looks right now, or you are going to make changes according to your personal taste, simply `git clone` is recommended. 

## License

Codes are available under the MIT License. 