docker-build-helper
===================

This is a Little tool that you can config to automaticly pull a git repository with docker build -t bla/bla

it checks if the docker build command is only docker build -t bla/bla if it is it will extract bla/bla
will check if a repo exists with the name docker-bla or bla in github account and build it

it also wraps docker pull 
