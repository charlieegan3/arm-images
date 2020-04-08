# alpine-curl

This is an image that is needed for my photos project.

Because I can't get arm go images to build on drone, I need to use cross
compilation, this means I need to use an amd64 pipeline, which means I can't
build a go binary and copy it into an alpine image AND install curl all at the
same time...
