# Vesl

Vesl Website: [vesl.sh](http://vesl.sh)

The goal of vesl is to be the easiest 
environment to use with all the tools and 
configurations you need for CMS development 
included out-of-the-box. That makes vesl an
excellent candidate for training purposes,
demos, and things like code sprints where
ease of setup and consistency are more 
important than extensibility. If you
require a more custom and robust experience
where you can use your own tools, we 
suggest you check out one of the other 
amazing projects that are doing something 
similar in a production ready way
([lando](https://github.com/lando/lando),
[docksal](https://github.com/docksal/docksal),
[blt](https://github.com/acquia/blt)).

## Getting started
To test this project out locally you can clone it
and create a symlink in your path.

On Ubuntu that would look something like this:
(make sure you have git and docker already installed)
```
cd ~/Downloads
git clone git@github.com:veslsh/vesl.git
sudo ln -s ~/Downloads/vesl/vesl /usr/local/bin/vesl
```

If you want to use this project ongoing, you might want to 
move the script somewhere besides your Downloads folder
where it's likely to get deleted.

## Vesl Blueprints
Most of the magic for this project does not actually happen
in the script that you download here. Everything is setup
to use preconfigured docker images based on the type of
project you are embarking on. Currently vesl only supports
Drupal and Wordpress images, but the system is designed for
you to add your own images (Blueprints) if you'd like.

The vesl blueprints live on Docker Hub: https://hub.docker.com/u/vesl/
