# UserStyles Collection 
[top]: #userstyles-collection

## [Install](#install) • [Styles](#styles) • [FAQ](#faq) • [Contribute](#contribute)


• • • 
<!-- TODO: Add preview images -->

Improve your browser experience by using dark themes for various sites.

The repo contains `.css` files I have created in order to improve experience of internet browsing of web sites that don't support dark mode by default.

## INSTALL
[install]: #install
> The project is mirrored at: [github][github mirror], [gitlab][gitlab mirror], and [bitbucket][bitbucket mirror] mirrors.

[github mirror]: https://github.com/hinell/user-css
[gitlab mirror]: https://gitlab.com/hinell/user-css
[bitbucket mirror]: https://bitbucket.org/hinell/user-css

To be able to use userstyles in your browser you have to install plugin that injects stylesheet files like [`Stylus`][stylus], `Stylish` etc. They have to support specific [user-css][styles-user-css] format (header & styles).


## STYLES
[styles]: #styles

The following stylesheets are listed under [`./userstyles/`](./userstyles/): 

* [Wikipidia](./userstyles/wikipedia.org/README.md)
<br/>Styles for various Wikimedia Foundation sites like wikipedia, wiktionary, wikibooks, etc. Multi-language is supported.


* [Git Docs Dark](./userstyles/git-docs-local/README.md)
<br/>Styles for locally available git documetation html pages. Documentation wchich is typically accessed via `git help -w <git command>` command.

* [Npm Dark](./userstyles/npm-docs-local/README.md)
<br/>Styles for locally available npm documetation wchich is typically accessed via `npm help <git command>` command.

* [en.cppreference.com](http://en.cppreference.com)
<br/>Styles for network/filesystem available cpp reference documetation. Documentation can typically be accessed via either [en.cppreference.com](en.cppreference.com) or locally: via downloading & installing local HTML book from [archives][en-cppreference-archive] . <git command>` command.

* [gnu.org](userstyles/gcc.gnu.org/gcc.gnu.org.user.css/README.md)</br>
Styles for GNU manuals (`bash`, `make`, `gawk`) in `/manuals` namespace. As of 2022 should work well for many pages. You can download and unzip manuals into `devdocs/gnu/(bash|make|gawk)/..` folder and read offline with dark styles applied. See `@-moz-document` in [user.css](userstyles/gnu.org/dark.user.css) for exact regexp used.

* [gcc.gnu.org](userstyles/gcc.gnu.org/gcc.gnu.org.user.css/README.md)</br>
<!-- TODO: Update this -->
Styles for for GCC STD C++  Library api.

## FAQ
[faq]: #faq

### What is the User CSS?
[faq-1]: #what-is-the-user-css

It's any [css] file that is specifically named (suffixed) by `.user.css` extension. Such files typically special header at the top. More info can be found here [here][styles-user-css].

## TODO
* add common palette
* add sass

## Contribute
[contribute]: #contribute
See [DEVELOPMENT.md] file for more info.
## Changelog
[changelog]: #changelog

<!-- TODO: Generate -->

[↑ Go To Top][top]

---

The Project is proudly managed by [Lerna][ad-lerna].
<br/> Documented by [README.MD][ad-readme].
<br/>

---

Copyright 2019 © Alexander Davronov &lt;al.neodim at gmail.com&gt; 
<br/> 

[0]: https://twitter.com/biteofpie
[css]: https://en.wikipedia.org/wiki/CSS
[ad-lerna]: https://lerna.js.org/
[ad-readme]: https://github.com/hinell/project-boilerplate/blob/master/README.md
[stylus]: https://github.com/openstyles/stylus
[styles-user-css]: https://github.com/openstyles/stylus/wiki/Writing-UserCSS
[en-cppreference-archive]: https://en.cppreference.com/w/Cppreference:Archives

[DEVELOPMENT.md]: ./DEVELOPMENT.md