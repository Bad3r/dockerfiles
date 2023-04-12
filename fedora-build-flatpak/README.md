# Fedora-Build-Flatpak
This docker image is used to build flatpaks using node. Specifically The logseq flatpak (https://github.com/bad3r/logseq-flatpak)

## Instructions
build & run the image
```sh
$ docker build --tag fedora-flatpak:latest .
$ docker run --rm -it -v /path/to/repo:/flatpak fedora-flatpak:latest
```
Replace the path with your local repo path; this should be an easy way to confirm the issue.
