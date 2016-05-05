# pelican-dockerfile
A base docker setup that inherits Python 2 and loads a bunch of deps. It runs Pelican in autoload mode for dev.

This is an easy to use image to setup a Pelican static website.
This image will run the Pelican devserver, which means it will watch for changes in the content and theme files.

Also a volume has been added so you can simply map to an existing Pelican directory and the container will update the output.

Some sane requirements have been pre-built into the image.

The DockerHub repository can be found here: https://hub.docker.com/r/mjjacko/pelican/

![Using the image](http://i.giphy.com/l41Yhz2wayIiyCyQM.gif)
