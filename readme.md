# GoodDocs Project -- Site

Currently this repository serves as the homepage for [The Good Docs Project](https://thegooddocsproject.dev/)


## Building Jekyll

There is an assumption here you have setup a ruby environment previously.  Those instructions unfortunately are out of scope for this project.

The current ruby version is `2.6.3` and Bundle `2.1.4`.  If you make updates to the `Gemlock` file please update this readme.

```shell
# install gems
gem install

# install pacakge using bundle
bundle install

# Build the content -- this sources the markdown and writes html to `_site/`
bundle exec jekyll build

# Takes the build at `_site/` and mounts it to a web-server
bundle exec jekyll serve
```

