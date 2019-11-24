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

This repo contains `.css` files which I have created in order to improve experience of internet browsing when visiting  sites which do not support dark mode. I've created a bunch of styles for ones I frequntly visit or use like Wikipedia, Twitter etc. Check out [`userstyles/`](./userstyles/) folder to find out more.



## INSTALL
[install]: #install

To be able to use userstyles in your browser you have to install plugin that injects stylesheet files akin to `Stylus`, `Stylish` etc.


## STYLES
[styles]: #styles

The following stylesheets are listed under `userstyles/`: 

* [wikipedia.dark.css](./userstyles/wikipedia.org/README.md)
<br/>Styles for various Wikimedia Foundation sites like wiktionary, wikibooks, etc


* [git-doc.dark.css](./userstyles/git-doc-local/README.md)
<br/>Styles for locally available git documetation html pages. Documentation may be accessed via `git help <git command>` command.


* [your.style.css](./userstyles/new/README.md)
<br/>You may contribute to this repo by opening up a pull request!


## FAQ
[faq]: #faq

### What is the UserStyle?
[faq-1]: #what-is-the-userstyle

Basically it's any `.css` (Cascading Style Sheet) file that becomes a userstyle when it replaces deafult site's styles.


## Contribute
[styles]: #contribute

The projet maintanance is government by two tools: `git-cz` and `lerna`. Good point to start with contribution is to checkout [`package.json`](./package.json) file scripts first.

| command | description
|-|-|
|`$ npm run cz`| commit changes by using `git-cz` |
|`$ npx lerna create <pkg name>`| create new userstyle |


[↑ Go To Top][top]

---
The Project is proudly managed by [Lerna][ad-lerna].
<br/> Documented by README.MD.
<br/>
Copyright 2019 © Alexander Davronov &lt;al.neodim@gmail.com&gt; 
<br/> 

[0]: https://twitter.com/biteofpie
[ad-lerna]: https://lerna.js.org/
[ad-readme]: https://lerna.js.org/
