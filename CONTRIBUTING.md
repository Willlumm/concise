# Contributing

## Setup

### Install Ruby

https://jekyllrb.com/docs/installation/windows/

1. Check the version of Ruby used by the [jekyll-build-pages](https://github.com/actions/jekyll-build-pages) GitHub action (v3.3 as of writing).

1. From the [RubyInstaller Downloads](https://rubyinstaller.org/downloads/), install the latest compatible x64 installer with Devkit for the appropriate Ruby version.

1. Run the `ridk install` step and choose the `MSYS2 and MINGW development toolchain` option.

1. Confirm the Ruby version with `ruby -v`. If another version is installed, you may have to uninstall it.

### Install RubyGems

https://rubygems.org/pages/download

### Install Jekyll

https://jekyllrb.com/docs/step-by-step/01-setup/

1. Check the version of Jekyll used by the [jekyll-build-pages](https://github.com/actions/jekyll-build-pages) GitHub action (v3.10.0 as of writing).

1. Run the following with the appropriate version flag for Jekyll:

```shell
gem install bundler
gem install jekyll -v 3.10.0
bundle init
```

1. Confirm the Jekyll version with `bundle exec Jekyll -v`.

## Development

Run `bundle exec jekyll serve` to build the site locally.

## Resources

- [Jekyll](https://jekyllrb.com/docs/)
- [Liquid](https://shopify.github.io/liquid/)
- [Sass](https://sass-lang.com/documentation/)
