# Jasecoop Jekyll

This Jekyll site is stripped down to allow for quick setup on a new Jekyll project that requires use of Heroku and the asset-pipeline. It is based on [jbhannah blog post] on compiling for Heroku. It'll allow for a simple push to Heroku and you'll be up and running.


## Asset Pipeline
For more details on the asset-pipeline and setup see:
https://github.com/matthodan/jekyll-asset-pipeline

## Deployment

The site is [compiled][] by [Jekyll][] when pushed to [Heroku][]. The
site on Heroku runs on a single dyno with no addons and the
[`user-env-compile`][] Labs feature.

## Copyright

This site in source code form is liscensed under the [MIT License][],
except for plugins that specify other licensing terms. The content as
compiled and displayed at [jbhannah.net][] is licensed under [Creative
Commons BY-NC-SA 3.0][CC BY-NC-SA].

[jbhannah blog post]: http://jbhannah.net/blog/2013/01/16/jekyll-on-heroku-without-rack-jekyll-or-custom-buildpacks.html
[compiled]: http://jbhannah.net/blog/2013/01/16/jekyll-on-heroku-without-rack-jekyll-or-custom-buildpacks.html
[Jekyll]: http://jekyllrb.com/
[Heroku]: http://www.heroku.com/
[`user-env-compile`]: https://devcenter.heroku.com/articles/labs-user-env-compile
[MIT License]: https://github.com/jbhannah/jbhannah.net/blob/master/LICENSE.txt
[jbhannah.net]: http://jbhannah.net/
[CC BY-NC-SA]: http://creativecommons.org/licenses/by-nc-sa/3.0/
