
<p align="center">
  <img title="portainer" src='https://portainer.io/images/logo_alt.png' />
</p>

[![Docker Pulls](https://img.shields.io/docker/pulls/portainer/portainer.svg)](https://hub.docker.com/r/portainer/portainer/)
[![Microbadger](https://images.microbadger.com/badges/image/portainer/portainer.svg)](http://microbadger.com/images/portainer/portainer "Image size")
[![Documentation Status](https://readthedocs.org/projects/portainer/badge/?version=stable)](http://portainer.readthedocs.io/en/stable/?badge=stable)
[![Codefresh build status]( https://g.codefresh.io/api/badges/build?repoOwner=portainer&repoName=portainer&branch=develop&pipelineName=portainer-ci&accountName=deviantony&type=cf-1)]( https://g.codefresh.io/repositories/portainer/portainer/builds?filter=trigger:build;branch:develop;service:5922a08a3a1aab000116fcc6~portainer-ci)
[![Slack](https://portainer.io/slack/badge.svg)](https://portainer.io/slack/)
[![Gitter](https://badges.gitter.im/portainer/Lobby.svg)](https://gitter.im/portainer/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YHXZJQNJQ36H6)

**_Portainer_** is a lightweight management UI which allows you to **easily** manage your different Docker environments (Docker hosts or Swarm clusters).

**_Portainer_** is meant to be as **simple** to deploy as it is to use. It consists of a single container that can run on any Docker engine (can be deployed as Linux container or a Windows native container).

**_Portainer_** allows you to manage your Docker containers, images, volumes, networks and more ! It is compatible with the *standalone Docker* engine and with *Docker Swarm mode*.

## Demo

<img src="https://portainer.io/images/screenshots/portainer.gif" width="77%"/>

You can try out the public demo instance: http://demo.portainer.io/ (login with the username **admin** and the password **tryportainer**).

Please note that the public demo cluster is **reset every 15min**.

## Getting started

* [Deploy Portainer](https://portainer.readthedocs.io/en/latest/deployment.html)
* [Documentation](https://portainer.readthedocs.io)
* <a href="BuildLocallyInWindows.md">Build Locally In Windows (cmd)</a>

## Getting help

* Issues: https://github.com/portainer/portainer/issues
* FAQ: https://portainer.readthedocs.io/en/latest/faq.html
* Slack (chat): https://portainer.io/slack/
* Gitter (chat): https://gitter.im/portainer/Lobby

## Reporting bugs and contributing

* Want to report a bug or request a feature? Please open [an issue](https://github.com/portainer/portainer/issues/new).
* Want to help us build **_portainer_**? Follow our [contribution guidelines](https://portainer.readthedocs.io/en/latest/contribute.html) to build it  locally and make a pull request. We need all the help we can get!

## Limitations

**_Portainer_** has full support for the following Docker versions:

* Docker 1.10 to the latest version
* Docker Swarm >= 1.2.3

Partial support for the following Docker versions (some features may not be available):

* Docker 1.9
