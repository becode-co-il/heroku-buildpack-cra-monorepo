# heroku-buildpack-custom-procfile

This buildpack is intended to allow a using a custom folder, ex. from a workspace in yarn.

```
heroku buildpacks:add "https://github.com/becode-co-il/heroku-buildpack-cra-monorepo.git" -a <yourappname>
heroku config:set APP_FOLDER="<path/to/app_folder>" -a <yourappname>

```
