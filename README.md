elizabrock.com
--------------

## Development Setup

This site is generated by [Jekyll](http://jekyllrb.com/). [Ruby](https://www.ruby-lang.org) is required to install/run Jekyll.

1. `bundle install` to install development dependencies.

You may need to `gem install bundler` if the `bundle` command is unavailable.

## Running Locally

Run `jekyll serve --watch` in the root of the project.

## Spell Checking

1. `brew install aspell`
2. `for f in **/*.md; do aspell check $f; done`
3. `for f in *.html; do aspell check $f; done`
4. `for f in **/*.html; do aspell check $f; done`

## Deploying

1. All code on master is automatically deployed by GitHub once it has been pushed to GitHub.
