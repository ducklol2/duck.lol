---
layout: post
title: "Publishing .local domains, automatically"
date: 2023-10-07 17:00:00 +0000
categories: jekyll update
---

My first thing! I've been playing with random things in
Docker containers on random local devices recently, but I didn't
like using IPs, or ports, or managing DNS servers, or adding DNS
entries to all my clients. I love how Traefik configures itself
based on Docker compose labels, so I made a tool that does the same
thing, but for using mDNS to publish `.local` addresses:

[github.com/ducklol2/quack_domains](https://github.com/ducklol2/quack_domains)

I swear that I looked around for something like this prior to
building it myself, and somehow I didn't find anything - but turns
out many others have built something similar. Check them out too, see
what makes sense to you!

- [gitlab.com/viraptor/docker_mdns](https://gitlab.com/viraptor/docker_mdns)
  - Written in Crystal, runs as a systemd service
- [github.com/hardillb/traefik-avahi-helper](https://github.com/hardillb/traefik-avahi-helper)
  - Written in JS & Python, runs as a container, monitors for changes
