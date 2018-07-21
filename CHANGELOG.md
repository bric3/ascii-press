# Changelog

## Version 2.0

* The main styles are refactored and redeveloped using SCSS (see [_static-src/scss_](https://github.com/htr3n/hyde-hyde/blob/master/static-src/scss))
  and we no longer need `poole.css` and `hyde.css` because `hyde-hyde.scss` already incorporates relevant elements
  * `Hyde-hyde` can be customised using [_static-src/scss/hyde-hyde/\_customised.scss_](https://github.com/htr3n/hyde-hyde/blob/master/static-src/scss/hyde-hyde/_customised.scss) and [_static-src/scss/hyde-hyde/\_variables.scss_](https://github.com/htr3n/hyde-hyde/blob/master/static-src/scss/hyde-hyde/_variables.scss) 
  * To generate `hyde-hyde.css`, please use any SCSS compiler to compile `hyde-hyde.scss`
* Restructuring/modularising further the layouts (see [_layouts_](https://github.com/htr3n/hyde-hyde/tree/v2.0.0/layouts))
* Add '[_Portfolio_](https://github.com/htr3n/hyde-hyde/tree/v2.0.0/layouts/portfolio)' page inspired by Xiaoying Riley ([@3rdwave_themes](https://twitter.com/3rdwave_themes)) [Developer-Theme](https://github.com/xriley/developer-theme)
* Setting the main body font to use system fonts (see [_static-src/scss/hyde-hyde/\_variables.css_](https://github.com/htr3n/hyde-hyde/tree/v1.0.0/static-src/scss/hyde-hyde/_variables.css))
	* In case you prefer Web fonts, just include the template "[web-fonts.html](https://github.com/htr3n/hyde-hyde/tree/v2.0.0/layouts/partials/header/web-fonts.html)" to "[header.html](https://github.com/htr3n/hyde-hyde/tree/v2.0.0/layouts/partials/header.html)"
* Switching to main fixed width font [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro)
* Adding OpenGraph and TwitterCard templates (for SEO)
* Adding '_Related Articles_' (see [_layouts/partials/post-related.html_](https://github.com/htr3n/hyde-hyde/tree/v2.0.0/layouts/partials/post-related.html))
* Adding page navigation _NEXT / PREVIOUS_
* Switching datetime format to `"Jan 02 '06"` in the list of posts (see [_layouts/partials/post-list.html_](https://github.com/htr3n/hyde-hyde/tree/v2.0.0/layouts/partials/post-list.html)) to save some space
* Changing styles for links, tags, text
* Adding some handy shortcodes for `<kbd></kbd>` and `<blockquote></blockquote>`
* The License under '_Some Rights Reversed_' in the sidebar is switched from [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/) to [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

## Version 1.0

* Color tones and layouts are inspired by [Nate Finch's blog](https://npf.io)
* Restructuring/modularising the layouts (see [`layouts/_default/baseof.html`](https://github.com/htr3n/hyde-hyde/tree/v1.0.0/layouts/_default/baseof.html), [`layouts/_default/single.html`](https://github.com/htr3n/hyde-hyde/tree/v1.0.0/layouts/_default/single.html), [`layouts/_default/list.html`](https://github.com/htr3n/hyde-hyde/tree/v1.0.0/layouts/_default/list.html) and [`layouts/partials`](https://github.com/htr3n/hyde-hyde/tree/v1.0.0/layouts/partials/))
* Using [highlight.js](https://highlightjs.org) for code highlighting
* Using [Font-Awesome 5](https://fontawesome.com)'s icons
* Using main font [Fira-Sans](https://fonts.google.com/specimen/Fira+Sans) + fixed width font [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono)
* Adding [GraphComment](https://graphcomment.com) for replacing the built-in [Disqus](https://disqus.com)
* Fork from [Hyde](https://github.com/spf13/hyde) 
* Adapt to [Nate Finch's blog](https://npf.io)'s colors and fonts.
* Refactor `basedof.html` and corresponding pages `index.html`, `single.html`, `list.html`
    - define blocks `content` and `footer` that will be fulfilled by each different type of layout.
