# What is devpi-server?

`devpi-server` is an efficient self-updating PyPI caching mirror.

# How to use this image

## Start an instance of devpi-server

You can start a `devpi-server` container like this:

    $ docker run \
        --publish 3141:3141 \
        --volume $HOME/devpidata:/data \
        goodtune/devpi-server

which allows you to access `devpi-server` through your browser at [localhost:3141](http://localhost:3141).
