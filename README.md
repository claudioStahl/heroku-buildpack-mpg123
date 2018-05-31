Heroku buildpack: mpg123
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for using mpg123 in your project.
It doesn't do anything else, so to actually compile your app you should use [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) to combine it with a real buildpack.

You can verify that mpg123 is installed by calling:

    $ heroku run "mpg123"
