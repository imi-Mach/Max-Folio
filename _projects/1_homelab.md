---
layout: page
title: Home Lab
description: Self-built Proxmox hypervisor hosting web services, gaming servers, Discord bots, IoT devices, and a development environment.
img: assets/img/project/proxmox.png
importance: 1
category: 2023
---

*January 2023 – Present · [mkmachado.com/homelab](https://mkmachado.com/homelab)*

I maintain a Proxmox hypervisor that hosts a variety of services including HTTPS web services, TCP gaming servers, Discord bots, and IoT devices. It also provides an environment for code-development tools.

Each service runs in an isolated virtual infrastructure that complies with **IEEE 802.1Q**. To ensure secure routing of SSL-encrypted web-service traffic, I use reverse proxies, Dynamic DNS, and VPN interfaces.

{% include figure.liquid loading="eager" path="assets/img/project/proxmox.png" title="Proxmox hypervisor dashboard" class="img-fluid rounded z-depth-1" %}
