# UserStyles Collection 
[top]: #userstyles-collection

<center>
• <a href="#install">Install</a>
• <a href="#styles">Styles</a>
• <a href="#faq">FAQ</a>
• <a href="#contribute">Contribute</a>
•
</center>

> _UNOpinated collection of userstyles_

<center> • • • </center>

This repo contains `.css` files which I have created in order to improve experience of internet browsing when visiting  sites which do not support dark mode. I've created a bunch of styles for the ones that I frequntly visit like Wikipedia, Twitter etc. Check out [`userstyles/`](./userstyles/) folder to find out more.



## INSTALL
[install]: #install

To be able to use userstyles in your browser you have to install plugin that injects stylesheet files akin to `Stylus`, `Stylish` etc.


## STYLES
[styles]: #styles

The following stylesheets are listed under `userstyles/`: 

* [wikipedia.dark.css](./userstyles/wikipedia.org/README.md)
<br/>Styles for various Wikimedia Foundation sites akin to wiktionary, wikibooks, etc


* [git-docs.dark.css](./userstyles/git-docs-local/README.md)
<br/>Styles for locally available git documetation html pages. Documentation wchich is typically accessed via `git help <git command>` command.

* [npm-docs.dark.css](./userstyles/npm-docs-local/README.md)
<br/>Styles for locally available npm documetation. Documentation wchich is typically accessed via `npm help <git command>` command.


* [your.superb.style.css](./userstyles/new/README.md)
<br/>You may [contribute][contribute] your own styles to this repo by opening up a PR! 

## FAQ
[faq]: #faq

### What is the UserStyle?
[faq-1]: #what-is-the-userstyle

Basically it's any `.css` (Cascading Style Sheet) file that becomes a userstyle when it replaces deafult site's styles.


## Contribute
[contribute]: #contribute

The projet maintanance is government by two tools: `git-cz` and `lerna`. Good point to start with contribution is to checkout [`package.json`](./package.json) file scripts first.

| command | description
|-|-|
|`$ npm run cz`| commit changes by using `git-cz` |
|`$ npx lerna create <pkg name>`| create new userstyle |


## Changelog
[changelog]: #changelog

TODO Generate

[↑ Go To Top][top]

---

The Project is proudly managed by [Lerna][ad-lerna].
<br/> Documented by [README.MD][ad-readme].
<br/>

---

Copyright 2019 © Alexander Davronov &lt;al.neodim@gmail.com&gt; 
<br/> 

[0]: https://twitter.com/biteofpie
[ad-lerna]: https://lerna.js.org/
[ad-readme]: https://github.com/hinell/project-boilerplate/blob/master/README.md
