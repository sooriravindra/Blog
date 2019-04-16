# Blog

Souce for my blog lies here :)

Powered by Jekyll and [pixyll.com](http://www.pixyll.com)

# Notes to build

Install ruby, ruby-dev using package manager and then :

```
$ gem install bundler jekyll
$ bundle install
$ bundle exec jekyll serve --watch
```
To create a new post:

`
$ rake post[sample_title_no_spaces]
`

then change the corresponding file created under the `_posts` directory to update the post.

