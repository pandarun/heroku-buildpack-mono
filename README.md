# Mono Heroku Buildpack

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpack) for Mono that will run ~~[ASP.NET](http://friism.com/running-net-on-heroku)~~ and [Katana/OWIN SelfHost applications](http://friism.com/running-owin-katana-apps-on-heroku).

It uses [nginx](http://www.mono-project.com/FastCGI_Nginx) as the web server and runs on Mono 3.2.8.

customized for dokku with OWIN Self-Hosted app.

[ORIGINAL](https://github.com/friism/heroku-buildpack-mono)

## Usage

+ install [dokku-multi-buildpack](https://github.com/pauldub/dokku-multi-buildpack) to dokku
+ add .buildpacks to git repository root and write this repository path
+ get [it](https://github.com/wilfrem/KatanaTest) and push to dokku
 
