# beta-development

A composite project with all required projects as submodules.
```
$ git -v
$ docker -v
$ docker-compose -v
$ git clone git@bitbucket.com:<project>/development.git <project> && cd <project>
$ git submodule init && git submodule update --remote
$ docker-compose up -d
```
To add a module to the project use the following command
```
git submodule add -b [branch] [URL to Git repo]
```
Inspired by:
https://www.airpair.com/docker/posts/efficiant-development-workfow-using-git-submodules-and-docker-compose
