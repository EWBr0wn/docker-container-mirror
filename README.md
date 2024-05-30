# Docker Container Mirror
Docker Container Mirror on GitHub powered by Github Actions and [Crane](https://github.com/google/go-containerregistry/tree/main/cmd/crane)

[![GitHub Workflow Status (branch)][github-actions-badge]][github-actions-link]

GitHub Actions scheduled to run daily at Midnight UTC to mirror some images to [GHCR.io](https://ghcr.io), bypassing rate limits

Mirrored Images:
* [`alpine`](https://ghcr.io/EWBr0wn/alpine)
* [`centos`](https://ghcr.io/EWBr0wn/centos)
* [`debian`](https://ghcr.io/EWBr0wn/debian)
* [`haproxy`](https://ghcr.io/EWBr0wn/haproxy)
* [`jitsi/jicofo`](https://ghcr.io/EWBr0wn/jitsi/jicofo)
* [`jitsi/jvb`](https://ghcr.io/EWBr0wn/jitsi/jvb)
* [`jitsi/prosody`](https://ghcr.io/EWBr0wn/jitsi/prosody)
* [`jitsi/web`](https://ghcr.io/EWBr0wn/jitsi/web)

[github-actions-badge]: https://img.shields.io/github/actions/workflow/status/EWBr0wn/docker-container-mirror/mirror.yml?branch=master "Github Workflow Status (master)"
[github-actions-link]: https://github.com/EWBr0wn/docker-container-mirror/actions?query=workflow%3AMirror%20Docker%20Containers
