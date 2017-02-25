# Fog City Ruby: A Website

### To develop

Install [Middleman](https://middlemanapp.com/) `gem install middleman`

`git checkout source`

`bundle`

`bundle exec middleman server`

Navigate to http://localhost:4567

Commit your changes to the `source` branch and push them up to GitHub.

### To deploy

Run `middleman deploy`. This will build all the stuff in the source directory, put it in the build dir, and push it to master.

Which means it will be deployed. :tada:
