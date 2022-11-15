# zsh-tailscale-plugin
This repository is my implementation of an autocomplete plugin for the tailscale CLI.

# Tailscale plugin

This plugin adds auto-completion and aliases for [tailscale](https://www.tailscale.com/).

To use it add `tailscale` to the plugins array in your zshrc file.

```zsh
plugins=(... tailscale)
```


## Aliases

| Alias   | Command                     | Description                                                                              |
| :------ | :-------------------------- | :--------------------------------------------------------------------------------------- |
|         |                             | **Common Commands**                                                                      |
|         | `tailscale up`              | Up connects your device to Tailscale                                                     |
|         | `tailscale down`            | Down disconnects your device from Tailscale                                              |
|         | `tailscale file`            | Access and make files available to Taildrop                                              |
|         | `tailscale cert`            | Generate certificate and key files on the host for HTTPS certificates in the network     |
|         | `tailscale ip`              | IP returns a device’s Tailscale IP address                                               |
|         | `tailscale logout`          | Log out disconnects from Tailscale, expires current login                                |
|         | `tailscale netcheck`        | Netcheck provides a report on your current physical network conditions                   |
|         | `tailscale ping`            | Ping tries to ping another device exclusively over Tailscale                             |
|         | `tailscale status`          | Status shows the status of your connections to other Tailscale devices                   |
|         | `tailscale web`             | Web starts a webserver for controlling the tailscaled daemon                             |
|         | `tailscale bugreport`       | Bugreport prints a random identifier into diagnostic logs                                |
|         | `tailscale version`         | Version prints the installed version of Tailscale                                        |
