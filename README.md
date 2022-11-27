# Home Assistant Community Add-on: Portainer

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[![Github Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

Manage your Docker environment with ease.

![The Portainer Hass.io add-on](images/screenshot.png)

## About

Portainer is an open-source lightweight management UI which allows you to
easily manage a Docker host(s) or Docker swarm clusters.

It has never been so easy to manage Docker. Portainer provides a detailed
overview of Docker and allows you to manage containers, images, networks and
volumes.

[:books: Read the full add-on documentation][docs]

## DISCONTINUED

This add-on is no longer available.

It has been used quite a lot for unsupported porposes, causing many issues,
support questions and other problems.

If you run Home Assistant, please be aware that running additional containers
is not a supported use-case and will trigger your system to be flagged
as unsupported as well.

## WARNING 1

The Portainer add-on is really powerful and gives you access to virtually
your whole system. While this add-on is created and maintained with care and
with security in mind, in the wrong or inexperienced hands,
it could damage your system.

## WARNING 2

The Portainer add-on is meant for debugging Home Assistant and its containers.
It has not meant or designed for managing or deploying your custom software
or third-party containers.

**Home Assistant DOES NOT SUPPORT running third party containers**
on Home Assistant OS or Supervised installation types. Ignoring this, will
render your system as unsupported!

## Support

Got questions?

You could also [open an issue here][issue] GitHub.

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](,github/CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Authors & contributors

The original setup of this repository is by [Franck Nijhof][frenck].

For a full list of all authors and contributors,
check [the contributor's page][contributors].

## We have got some Home Assistant add-ons for you

Want some more functionality to your Home Assistant instance?

We have created multiple add-ons for Home Assistant. For a full list, check out
our [GitHub Repository][repository].

## License

MIT License

Copyright (c) 2018-2021 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/hassio-addons/addon-portainer.svg
[commits]: https://github.com/mib1185/homeassistant-addon-portainer/commits/main
[contributors]: https://github.com/mib1185/homeassistant-addon-portainer/graphs/contributors
[docs]: https://github.com/mib1185/homeassistant-addon-portainer/blob/main/portainer/DOCS.md
[github-actions-shield]: https://github.com/mib1185/homeassistant-addon-portainer/workflows/CI/badge.svg
[github-actions]: https://github.com/mib1185/homeassistant-addon-portainer/actions
[i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[issue]: https://github.com/mib1185/homeassistant-addon-portainer/issues
[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-%20!%20DEPRECATED%20%20%20!-ff0000.svg
[releases-shield]: https://img.shields.io/github/release/hassio-addons/addon-portainer.svg
[releases]: https://github.com/mib1185/homeassistant-addon-portainer/releases
[repository]: https://github.com/hassio-addons/repository
[frenck]: https://github.com/frenck
