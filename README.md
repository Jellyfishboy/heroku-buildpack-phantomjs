Heroku buildpack: PhantomJS
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of PhantomJS(http://phantomjs.org).

This buildpack contains PhantomJS v1.9.8

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/Jellyfishboy/heroku-buildpack-phantomjs.git

# or if your app is already created:
$ heroku config:add BUILDPACK_URL=https://github.com/Jellyfishboy/heroku-buildpack-phantomjs.git

$ git push heroku master
```
