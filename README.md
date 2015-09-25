# beta-development

A composite project with all required projects as submodules.

To start from scratch:
```
git -v
docker -v
docker-compose -v
git clone https://github.com/carlhuk/beta-development.git <project> && cd <project>
git submodule init && git submodule update --remote
docker-compose up -d
```
To add a module to the project use the following command
```
git submodule add -b [branch] [URL to Git repo]
```

# Installing docker compose
```
# Install docker-compose
sudo sh -c "curl -L https://github.com/docker/compose/releases/download/1.4.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose"
sudo chmod +x /usr/local/bin/docker-compose
sudo sh -c "curl -L https://raw.githubusercontent.com/docker/compose/1.4.0/contrib/completion/bash/docker-compose > /etc/bash_completion.d/docker-compose"
```

Inspired by:
https://www.airpair.com/docker/posts/efficiant-development-workfow-using-git-submodules-and-docker-compose
