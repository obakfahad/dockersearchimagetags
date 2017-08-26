# Docker Search Image Tags

By this script you can get list of tags of certain image. Normally docker search command doesn't give you functionality to find what are the available tags.

Knowing exact tags can save some space and confusion.

## Installation
`mkdir $HOME/bin;wget https://ourl.us/k2z2u -O $HOME/bin/docker-search;chmod a+x $HOME/bin/docker-search`

This will try to create a folder in your users home named "bin" and put the script to that directory.

## USAGE

`$ docker-search ubuntu`

Output:

ubuntu:16.04
ubuntu:17.04
ubuntu:latest
ubuntu:rolling
ubuntu:trusty
ubuntu:trusty-20170728
ubuntu:xenial
ubuntu:xenial-20170802
ubuntu:zesty
ubuntu:zesty-20170703
