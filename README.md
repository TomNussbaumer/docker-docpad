# docker-docpad

[![](https://badge.imagelayers.io/sys42/docker-docpad:latest.svg)](https://imagelayers.io/?images=sys42/docker-docpad:latest 'Get your own badge on imagelayers.io')

[Docpad](http://docpad.org/) embedded in a Docker Container.

Docpad is a static website generator which supports many different website templates like Twitter Bootstrap, markup languages like Markdown and templating engines and of course github pages integration. You can see it as a better variant of [Jekyll](http://www.jekyllnow.com/). 

For a qick start, enter an empty directory and type `docpad run`. More infos can be found [here](http://docpad.org/docs/intro).

**NOTE:** Due the UID/GID remapping on startup and the local installation of node in user app's home directory, it may take a while until the container is started.

----------------------------------------------------

For generic usage informations of this image please examine [the README file of the base image](https://github.com/sys42/docker-base).

