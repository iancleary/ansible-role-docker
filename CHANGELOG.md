# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

---

## [5.0.0] - 2022-09-01

- Switch to `docker.io` apt package and `docker-compose` pip (Python) package.to allow docker and docker-compose control via Ansible.  Main benefits are not having to manage architecture version nor manage docker-compose executables.

* https://docs.ansible.com/ansible/latest/collections/community/docker/docker_image_module.html
* https://docs.ansible.com/ansible/latest/collections/community/general/docker_compose_module.html


## [4.1.0] - 2022-07-12

### Changed

- Added support for Ubuntu 22.04 [#12](https://github.com/iancleary/ansible-role-docker/pull/12)

## [4.0.1] - 2022-01-19

### Changed

- corrected ansible galaxy supported platforms

## [4.0.0] - 2022-01-19

### Changed

- username from `icancclearynow` to `iancleary`

## [3.0.0] - 2021-08-29

### Changed

- username from `iancleary` to `icancclearynow`

## [2.0.2] - 2021-08-13

### Changed

- Added more specific when conditionals for Ubuntu 20.04 and elementary OS 6

## [2.0.1] - 2021-08-12

### Changed

- Bumped docker-compose to [1.29.2](https://github.com/docker/compose/releases/tag/1.29.2)

## [2.0.0] - 2021-08-12

### Changed

- Switched to root user with `become: true`

### Removed

- Removed start on boot command, since it is already the [default on Debian and Ubuntu based systems](https://docs.docker.com/engine/install/linux-postinstall/#configure-docker-to-start-on-boot)

## [1.0.1] - 2021-03-28

### Changed

- Bumped docker-compose to [1.28.6](https://github.com/docker/compose/releases/tag/1.28.6)

## [1.0.0] - 2021-02-26

## Added

- Descriptions of role variables

### Changed

- Bumped docker-compose to [1.28.5](https://github.com/docker/compose/releases/tag/1.28.5)

## [0.1.0] - 2021-02-08

### Added

- Initial role! 🚀

[Unreleased]: https://github.com/iancleary/ansible-role-docker/compare/v5.0.0...HEAD
[5.0.0]: https://github.com/iancleary/ansible-role-docker/releases/tag/v5.0.0
[4.0.1]: https://github.com/iancleary/ansible-role-docker/releases/tag/v4.0.1
[4.0.0]: https://github.com/iancleary/ansible-role-docker/releases/tag/v4.0.0
[3.0.0]: https://github.com/iancleary/ansible-role-docker/releases/tag/v3.0.0
[2.0.2]: https://github.com/iancleary/ansible-role-docker/releases/tag/v2.0.2
[2.0.1]: https://github.com/iancleary/ansible-role-docker/releases/tag/v2.0.1
[2.0.0]: https://github.com/iancleary/ansible-role-docker/releases/tag/v2.0.0
[1.0.1]: https://github.com/iancleary/ansible-role-docker/releases/tag/v1.0.1
[1.0.0]: https://github.com/iancleary/ansible-role-docker/releases/tag/v1.0.0
[0.1.0]: https://github.com/iancleary/ansible-role-docker/releases/tag/v0.1.0
