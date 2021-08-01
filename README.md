# how-to-deploy-an-app-to-dokku






On your local

    gem install suspenders




Deploying an app

    Your bundle only supports platforms ["arm64-darwin-20"] but your local platform
       is x86_64-linux. Add the current platform to the lockfile with `bundle lock --add-platform x86_64-linux` and try again.
  
  If you see this, go to PLATFORMS in Gemfile.lock and delete them all and put just "ruby".
