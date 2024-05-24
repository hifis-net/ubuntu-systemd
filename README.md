# Systemd Ubuntu Container Images For Ansible and Podman

Systemd Ubuntu Container Images for testing roles with Molecule and Podman.
Supported Ubuntu versions:

* `24.04`
* `22.04`
* `20.04`

## Available Images

Images are built weekly via GitHub Actions and can be downloaded from the
GitHub Package Registry.

These tags are available. They are updated on changes to the `main` branch
and are automatically rebuilt once a week.

* `ghcr.io/hifis-net/ubuntu-systemd:24.04`
* `ghcr.io/hifis-net/ubuntu-systemd:22.04`
* `ghcr.io/hifis-net/ubuntu-systemd:20.04`

## How to Use

* [Install Podman](https://podman.io/getting-started/installation)
* Run the container via Podman:

  ```bash
  podman run -it --systemd=true --privileged ghcr.io/hifis-net/ubuntu-systemd:22.04
  ```

## Authors

This project is maintained by [HIFIS](https://www.hifis.net).
It is built upon https://github.com/geerlingguy/docker-ubuntu2204-ansible.
