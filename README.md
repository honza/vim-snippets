IMPORTANT: comment on: [What about merging whith Ultisnip using its engine](https://github.com/garbas/vim-snipmate/issues/114)

Snipmate Snippets
=================

This repository contains snippets files for various programming languages.

It was originally written for the the famous [snipMate][1] plugin for vim.
However today there are at least 3 plugins which can make use of this snippet repository:

1) [snipMate][1]

2) [Shougo's neosnippet][5] has a compatible mode allowing
  to reuse most snippets.

3) [ultisnip][6] (stable enough to be used, branch master previously snipmate-merge)
  This code is subject to change. Take it as preview. That branch
  has additional notes for Snipmate users. at the bottom.
  In the long run ultisnip will have its own set of snippets, because it is
  more powerful cause it supports nested snippets.



It is community-maintained and many people have contributed snippet files and other
improvements already. Not sure whether it implements all features such as
guards - does anybody know?

[vim-snipmate][1] was originally started by [Michael Sanders][2] who has now
unfortunately abandoned the project. [Rok Garbas][3] is now maintaining a
[fork][4] of the project in hopes of improving the existing code base.


Language maintainers
--------------------

No one can really be proficient in all programming languages. If you would like
to maintain snippets for a language, please get in touch.

* Python - [honza](http://github.com/honza)
* Javascript - [honza](http://github.com/honza)
* HTML Django - [honza](http://github.com/honza)
* Markdown - [honza](http://github.com/honza)
* Ruby - [taq](http://github.com/taq)
* PHP - [chrisyue](http://github.com/chrisyue)

Contributing notes
------------------

Until further work is done on `vim-snipmate`, please don't add folding markers
into snippets. `vim-snipmate` has some comments about how to patch all snippets
on the fly adding those.

Authors
-------

For a list of authors, please see the `AUTHORS` files.

License
-------

Just as the original snipMate plugin, all the snippets are licensed under the
terms of the MIT license.


[1]: http://github.com/garbas/vim-snipmate
[2]: http://github.com/msanders
[3]: http://github.com/garbas
[4]: http://github.com/garbas/vim-snipmate
[5]: https://github.com/Shougo/neosnippet
[6]: https://github.com/MarcWeber/UltiSnips/tree/snipmate-merge
