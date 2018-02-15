## HAProxy Buildpack

A Heroku buildpack to clean old vendored gems


There is a problem with bundler/heroku where old gems are not removed.
This is causing a PATH problem for me so this buildpack aims to address that problem.

See this [stackoverflow post](https://stackoverflow.com/questions/14533676/heroku-bundler-not-deleting-old-gems-versions)

