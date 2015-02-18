mediabrowser
============

This container runs [MediaBrowser](http://mediabrowser.tv/) on top of the
[jleight/phusion-mono](https://registry.hub.docker.com/u/jleight/phusion-mono/)
container.


Usage
-----

A MediaBrowser container can be started with very little extra configuration.
Here's a simple example that starts the container and opens port 8989:

```bash
# docker run
  --name mediabrowser \
  -p 8096:8096 \
  jleight/mediabrowser
```