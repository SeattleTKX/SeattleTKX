# Website for _Chinese Comedy at Silicon Valley_

The website is deployed to [GitHub pages](https://ggtkx.github.io/) and is served at [ggtkx.org](http://ggtkx.org/en/).

The Website is statically generated with [Jekyll](https://jekyllrb.com/). To serve it locally, run:

```shell
bundle exec jekyll serve
```



Data organization:
- `_data/comedians.json` stores information about each comedian in this club. It is updated automatically to sync up with a Google Sheet.
- `_data/friends.yml` stores links to our friends.
- `_team/` contains Markdown documents for each member of the core team.

Other technical details:
- `pull-sheet/` hosts the mechanism that updates `_data/comedians.json` from the roster.
- `sidenotes.js` is a pure-JavaScript plugin that puts `.footnotes` into `#sidebar`, aligning each piece of note at their corresponding superscript.
- This website uses the [Serif](https://github.com/zerostaticthemes/jekyll-serif-theme) theme by [Robert Austin](https://github.com/zerostaticthemes). See LICENSE.
