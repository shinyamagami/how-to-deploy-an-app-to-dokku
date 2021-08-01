# how-to-deploy-an-app-to-dokku






On your local

    gem install suspenders




Deploying an app

    Your bundle only supports platforms ["arm64-darwin-20"] but your local platform
       is x86_64-linux. Add the current platform to the lockfile with `bundle lock --add-platform x86_64-linux` and try again.
  
  If you see this warning, go to PLATFORMS in Gemfile.lock and delete any platforms and put just "ruby".
  After that, "bundle update" and "git commit".
  
  
  https://github.com/thoughtbot/suspenders/blob/main/docs/heroku_deploy.md
  dokku config:set APPLICATION_HOST=URL
