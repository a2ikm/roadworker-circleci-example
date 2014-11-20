CircleCI + Roadworker for AWS Route53
=====================================

```
bundle install
bundle exec roadworker -e -o Routefile
git init
git add .
git commit -m "Initial commit"
hub create
g push -u origin master
g co -B change_routes
vi Routefile
git add Routefile
git commit -m "Change routes"
git push -u origin change_routes
hub pull-request
```
