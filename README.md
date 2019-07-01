# heroku-buildpack-custom-procfile

This buildpack is intended to allow a using a custom Procfile, ex. from a workspace in yarn.

```
heroku buildpacks:add "https://github.com/Aulos/heroku-buildpack-custom-procfile#master" -a yourappname
heroku config:set CUSTOM_PROCFILE="path/to/Procfile" -a yourappname

```