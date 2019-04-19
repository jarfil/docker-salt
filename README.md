# Salt docker images

## Supported tags

* `latest`, `debian`, `debian-stretch`
* `debian-buster`
* `debian-unstable`
* `fedora`, `fedora-29`

## Layers

| Image | debian-stretch | debian-buster | debian-unstable |
| --- | --- | --- | --- |
| [salt-common](https://cloud.docker.com/repository/docker/jarfil/salt-common) | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-common:debian-stretch "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-common:debian-buster "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-common:debian-unstable "Get your own image badge on microbadger.com") |
| [salt-minion](https://cloud.docker.com/repository/docker/jarfil/salt-minion) | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-minion:debian-stretch "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-minion:debian-buster "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-minion:debian-unstable "Get your own image badge on microbadger.com") |
| [salt-master-mini](https://cloud.docker.com/repository/docker/jarfil/salt-master-mini) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master-mini:debian-stretch "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-master-mini:debian-buster "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-master-mini:debian-unstable "Get your own image badge on microbadger.com") |
| [salt-syndic](https://cloud.docker.com/repository/docker/jarfil/salt-syndic) | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-syndic:debian-stretch "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-syndic:debian-buster "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-syndic:debian-unstable "Get your own image badge on microbadger.com") |
| [salt-master](https://cloud.docker.com/repository/docker/jarfil/salt-master) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master:debian-stretch "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-master:debian-buster "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-master:debian-unstable "Get your own image badge on microbadger.com") |
| [salt-master-docs](https://cloud.docker.com/repository/docker/jarfil/salt-master-docs) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master-docs:debian-stretch "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-master-docs:debian-buster "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-master-docs:debian-unstable "Get your own image badge on microbadger.com") |
| [salt-full](https://cloud.docker.com/repository/docker/jarfil/salt-full) | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-full:debian-stretch "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-full:debian-buster "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-full:debian-unstable "Get your own image badge on microbadger.com") |

## Debian Stretch (9, stable)

Official SaltStack packages for [Debian 9 PY3 latest](https://repo.saltstack.com/#debian).

**Note:** package `salt-minion` includes `salt-proxy`.

| Image: | [common](https://cloud.docker.com/repository/docker/jarfil/salt-common) | [minion](https://cloud.docker.com/repository/docker/jarfil/salt-minion) | [master-mini](https://cloud.docker.com/repository/docker/jarfil/salt-master-mini) | [syndic](https://cloud.docker.com/repository/docker/jarfil/salt-syndic) | [master](https://cloud.docker.com/repository/docker/jarfil/salt-master) | [master-docs](https://cloud.docker.com/repository/docker/jarfil/salt-master-docs) | [full](https://cloud.docker.com/repository/docker/jarfil/salt-full) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| FROM: | debian | common | common | master-mini | master-mini | master | master-docs |
| **Packages** |
| salt-common | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-minion |  | ✔️ |  |  | ✔️ | ✔️ | ✔️ |
| salt-master |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-ssh |  |  |  |  | ✔️ | ✔️ | ✔️ |
| salt-cloud |  |  |  |  | ✔️ | ✔️ | ✔️ |
| salt-syndic |  |  |  | ✔️ |  |  | ✔️ |
| salt-api |  |  |  |  |  |  | ✔️ |
| man |  |  |  |  |  | ✔️ | ✔️ |
| less |  |  |  |  |  | ✔️ | ✔️ |
| salt-doc |  |  |  |  |  | ✔️ | ✔️ |
| **Autostart** |
| minion |  | ✔️ |  |  | ✔️ | ✔️ |  |
| master |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| syndic |  |  |  | ✔️ |  |  |  |  |

## Debian Buster (10, testing)

Official Debian packages.

| Image: | [common](https://cloud.docker.com/repository/docker/jarfil/salt-common) | [minion](https://cloud.docker.com/repository/docker/jarfil/salt-minion) | [master-mini](https://cloud.docker.com/repository/docker/jarfil/salt-master-mini) | [syndic](https://cloud.docker.com/repository/docker/jarfil/salt-syndic) | [master](https://cloud.docker.com/repository/docker/jarfil/salt-master) | [master-docs](https://cloud.docker.com/repository/docker/jarfil/salt-master-docs) | [full](https://cloud.docker.com/repository/docker/jarfil/salt-full) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| FROM: | debian | common | common | master-mini | master-mini | master | master-docs |
| **Packages** |
| salt-common | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-minion |  | ✔️ |  |  | ✔️ | ✔️ | ✔️ |
| salt-master |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-ssh |  |  |  |  | ✔️ | ✔️ | ✔️ |
| salt-cloud |  |  |  |  | ✔️ | ✔️ | ✔️ |
| salt-syndic |  |  |  | ✔️ |  |  | ✔️ |
| salt-api |  |  |  |  |  |  | ✔️ |
| salt-pepper |  |  |  |  |  |  | ✔️ |
| salt-proxy |  |  |  |  |  |  | ✔️ |
| man |  |  |  |  |  | ✔️ | ✔️ |
| less |  |  |  |  |  | ✔️ | ✔️ |
| salt-doc |  |  |  |  |  | ✔️ | ✔️ |
| **Autostart** |
| minion |  | ✔️ |  |  | ✔️ | ✔️ |  |
| master |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| syndic |  |  |  | ✔️ |  |  |  |  |

## Debian Sid (unstable)

Official Debian packages.

| Image: | [common](https://cloud.docker.com/repository/docker/jarfil/salt-common) | [minion](https://cloud.docker.com/repository/docker/jarfil/salt-minion) | [master-mini](https://cloud.docker.com/repository/docker/jarfil/salt-master-mini) | [syndic](https://cloud.docker.com/repository/docker/jarfil/salt-syndic) | [master](https://cloud.docker.com/repository/docker/jarfil/salt-master) | [master-docs](https://cloud.docker.com/repository/docker/jarfil/salt-master-docs) | [full](https://cloud.docker.com/repository/docker/jarfil/salt-full) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| FROM: | debian | common | common | master-mini | master-mini | master | master-docs |
| **Packages** |
| salt-common | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-minion |  | ✔️ |  |  | ✔️ | ✔️ | ✔️ |
| salt-master |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-ssh |  |  |  |  | ✔️ | ✔️ | ✔️ |
| salt-cloud |  |  |  |  | ✔️ | ✔️ | ✔️ |
| salt-syndic |  |  |  | ✔️ |  |  | ✔️ |
| salt-api |  |  |  |  |  |  | ✔️ |
| salt-pepper |  |  |  |  |  |  | ✔️ |
| salt-proxy |  |  |  |  |  |  | ✔️ |
| man |  |  |  |  |  | ✔️ | ✔️ |
| less |  |  |  |  |  | ✔️ | ✔️ |
| salt-doc |  |  |  |  |  | ✔️ | ✔️ |
| **Autostart** |
| minion |  | ✔️ |  |  | ✔️ | ✔️ |  |
| master |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| syndic |  |  |  | ✔️ |  |  |  |  |

## Fedora 29

Official Fedora packages.

| Image: | [common](https://cloud.docker.com/repository/docker/jarfil/salt-common) | [minion](https://cloud.docker.com/repository/docker/jarfil/salt-minion) | [master-mini](https://cloud.docker.com/repository/docker/jarfil/salt-master-mini) | [syndic](https://cloud.docker.com/repository/docker/jarfil/salt-syndic) | [master](https://cloud.docker.com/repository/docker/jarfil/salt-master) | [master-docs](https://cloud.docker.com/repository/docker/jarfil/salt-master-docs) | [full](https://cloud.docker.com/repository/docker/jarfil/salt-full) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| FROM: | fedora | common | common | master-mini | master-mini | master | master-docs |
| **Packages** |   |   |   |   |   |   |   |
| salt         | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-minion  |   | ✔️ |   |   | ✔️ | ✔️ | ✔️ |
| salt-master  |   |   | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| salt-ssh     |   |   |   |   | ✔️ | ✔️ | ✔️ |
| salt-cloud   |   |   |   |   | ✔️ | ✔️ | ✔️ |
| salt-syndic  |   |   |   | ✔️ |   |   | ✔️ |
| salt-api     |   |   |   |   |   |   | ✔️ |
| man          |   |   |   |   |   | ✔️ | ✔️ |
| **Autostart** |   |   |   |   |   |   |   |
| minion |   | ✔️ |   |   | ✔️ | ✔️ |   |
| master |   |   | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| syndic |   |   |   | ✔️ |   |   |   |   |

