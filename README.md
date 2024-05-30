# Docker Container Mirror
Docker Container Mirror on GitHub powered by Github Actions and [Crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane)

[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link]

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:
* [`alpine`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Falpine)
* [`centos`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Fcentos)
* [`haproxy`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Fhaproxy)
* [`jitsi/jicofo`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Fjitsi/jicofo)
* [`jitsi/jvb`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Fjitsi/jvb)
* [`jitsi/prosody`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Fjitsi/prosody)
* [`jitsi/web`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Fjitsi/web)
* [`ubuntu`](https://github.com/EWBr0wn/docker-container-mirror/pkgs/container/mirror%2Fdocker.io%2Fubuntu)

[github-actions-badge]: https://img.shields.io/github/actions/workflow/status/EWBr0wn/docker-container-mirror/mirror.yml?branch=master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/EWBr0wn/docker-container-mirror/actions?query=workflow%3AMirror%20Docker%20Containers
