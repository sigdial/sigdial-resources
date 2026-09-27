# SIGdial resource list

This is the source repository for [SIGdial Resource Lists for Discourse and Dialogue Research](https://sigdial.github.io/sigdial-resources/), which is maintained by [SIGdial (Special Interest Group on Discourse and Dialogue)](https://www.sigdial.org/).

This repository is built with [Documentation Theme for Jekyll](https://idratherbewriting.com/documentation-theme-jekyll/). We want to thank Tom Johnson, the creator of the theme.

## Local development

Use Ruby 3.3 and Bundler 2.6.9:

```sh
gem install bundler -v 2.6.9
bundle install
bundle exec jekyll serve
```

The Gemfile lists only the dependencies used by this site's local theme and
Kramdown renderer. Avoid adding the `github-pages` meta-gem: it includes unused
plugins whose dependency constraints prevent security updates (for example,
`jekyll-remote-theme` requires `rubyzip < 3`, while the security fix needs 3.4.0).
GitHub Pages currently publishes the `gh-pages` branch using its managed build;
the Gemfile controls local builds, not the versions in that managed environment.

To check dependency security:

```sh
gem install bundler-audit
bundle-audit check --update
```
