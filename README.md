
Website using Indigo Minimalist Jekyll Template - <a href="http://sergiokopplin.github.io/indigo/">Demo</a> · <a href="https://travis-ci.org/sergiokopplin/indigo"><img src="https://camo.githubusercontent.com/5393485b732749b3499264168fa8af60166071e8/68747470733a2f2f7472617669732d63692e6f72672f73657267696f6b6f70706c696e2f696e6469676f2e7376673f6272616e63683d67682d7061676573" alt="Build Status" data-canonical-src="https://travis-ci.org/sergiokopplin/indigo.svg?branch=gh-pages" style="max-width:100%;"></a></h2>


## Setup

0. :star: to the project. :metal:
2. Fork the project [Indigo](https://github.com/sergiokopplin/indigo/fork)
3. Edit `_config.yml` with your data (check <a href="README.md#settings">settings</a> section)
4. Write some posts :bowtie:

If you want to test locally on your machine, do the following steps also:

1. Install [Jekyll](http://jekyllrb.com), [NodeJS](https://nodejs.org/) and [Bundler](http://bundler.io/).
2. Clone the forked repo on your machine
3. Enter the cloned folder via terminal and run `bundle install`
4. Then run `bundle exec jekyll serve --config _config.yml,_config-dev.yml`
5. Open it in your browser: `http://localhost:4000`
6. Test your app with `bundle exec htmlproofer ./_site`
7. Do you want to use the [jekyll-admin](https://jekyll.github.io/jekyll-admin/) plugin to edit your posts? Go to the admin panel: `http://localhost:4000/admin`. The admin panel will not work on GitHub Pages, [only locally](https://github.com/jekyll/jekyll-admin/issues/341#issuecomment-292739469).

## How To?

Check the [FAQ](./FAQ.md) if you have any doubt or problem.

---

[MIT](http://kopplin.mit-license.org/) License © Sérgio Kopplin
