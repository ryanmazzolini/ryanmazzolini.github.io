# Welcome

Welcome! My name is Ryan Mazzolini and you've found yourself at the source of my personal website/blog/portfolio.

To view the website head over to https://ryanmazzolini.github.io/

## Package

The package/website is built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub pages.
Currently, the [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) jekyll remote-theme is used.

### Building OSX

On OSX I install as much as I can via [Homebrew](https://brew.sh/).

#### Install Ruby
Get ruby if you don't have it already:
```sh
brew install ruby
```

Alternatively, I like using rbenv to manage multiple ruby version on a single machine:
```sh
brew install rbenv

# Install your desired version of ruby, replace the `3.3.6` bit
# Note bundler/jekyll require a Ruby version >= 3.0.0
rbenv install 3.3.6
# Switch to the version of ruby you have installed. 
# Use `global` instead of `local` if you want this to be the default globally
rbenv local 3.3.6
```

#### Jekyll

Install Bundler and Jekyll if not yet installed:
```sh
gem install bundler jekyll
```

Install missing gems:
```sh
bundle install
```

Start the local server:
```sh
bundle exec jekyll serve
```
Now browse to http://localhost:4000

## Redirect

There are currently two URLs that redirect to this site after tearing down an old Wordpress instance.
Those are:
- https://rmazzolini.com/
- https://ryanmazzolini.com/