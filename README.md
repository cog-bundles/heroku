# Heroku Bundle for [Cog](http://github.com/operable/cog)

## Commands

```
heroku:app
heroku:app list
heroku:app info <app>

heroku:config [--app app]
heroku:config list [--app app]
heroku:config set <name=value> [--app app]
heroku:config unset <name> [--app app]

heroku:ps [--app app]
heroku:ps list [--app app]
heroku:ps scale <name=dynos> ... [--app app]
heroku:ps restart <name> ...  [--app app]
heroku:ps stop <name> ...  [--app app]

heroku:release [--app app]
heroku:release list [--app app]
heroku:release info <release> [--app app]
heroku:release rollback <release>  [--app app]

heroku:user [--app app]
heroku:user list [--app app]
heroku:user add <email>  [--app app]
heroku:user remove <email>  [--app app]
```

## Credentials

The heroku bundle requires either a `HEROKU_API_KEY` or both a
`HEROKU_USERNAME` and `HEROKU_PASSWORD` to be set for communication with the
heroku api.
