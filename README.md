# Instructions

## To run locally (not on GitHub Pages, to serve on Mac)

1. Make sure you have ruby-dev, bundler, and nodejs installed: `brew install chruby ruby-install xz; ruby-install ruby 3.1.3;`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `gem install github-pages` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
1. Run `jekyll build; jekyll serve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

