# Salt docker images

## Supported tags

* `latest`, `debian`, `debian-stretch`
* `debian-buster`
* `debian-unstable`
* `fedora`, `fedora-29`

## Layers

| Image | debian-stretch | debian-buster | debian-unstable | fedora-29 |
| --- | --- | --- | --- | --- |
| [salt-common][salt-common] | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-common:debian-stretch) | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-common:debian-buster) | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-common:debian-unstable) | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:fedora-29.svg)](http://microbadger.com/images/jarfil/salt-common:fedora-29) |
| [salt-minion][salt-minion] | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-minion:debian-stretch) | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-minion:debian-buster) | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-minion:debian-unstable) | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:fedora-29.svg)](http://microbadger.com/images/jarfil/salt-minion:fedora-29) |
| [salt-master-mini][salt-master-mini] | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master-mini:debian-stretch) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-master-mini:debian-buster) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-master-mini:debian-unstable) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:fedora-29.svg)](http://microbadger.com/images/jarfil/salt-master-mini:fedora-29) |
| [salt-syndic][salt-syndic] | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-syndic:debian-stretch) | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-syndic:debian-buster) | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-syndic:debian-unstable) | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:fedora-29.svg)](http://microbadger.com/images/jarfil/salt-syndic:fedora-29) |
| [salt-master][salt-master] | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master:debian-stretch) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-master:debian-buster) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-master:debian-unstable) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:fedora-29.svg)](http://microbadger.com/images/jarfil/salt-master:fedora-29) |
| [salt-master-docs][salt-master-docs] | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master-docs:debian-stretch) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-master-docs:debian-buster) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-master-docs:debian-unstable) | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:fedora-29.svg)](http://microbadger.com/images/jarfil/salt-master-docs:fedora-29) |
| [salt-full][salt-full] | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-full:debian-stretch) | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-buster.svg)](http://microbadger.com/images/jarfil/salt-full:debian-buster) | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-unstable.svg)](http://microbadger.com/images/jarfil/salt-full:debian-unstable) | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:fedora-29.svg)](http://microbadger.com/images/jarfil/salt-full:fedora-29) |

## Debian Stretch (9, stable)

Official SaltStack packages for [Debian 9 PY3 latest](https://repo.saltstack.com/#debian).

**Note:** package `salt-minion` includes `salt-proxy`.

| Image: | [common][salt-common] | [minion][salt-minion] | [master-mini][salt-master-mini] | [syndic][salt-syndic] | [master][salt-master] | [master-docs][salt-master-docs] | [full][salt-full] |
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

| Image: | [common][salt-common] | [minion][salt-minion] | [master-mini][salt-master-mini] | [syndic][salt-syndic] | [master][salt-master] | [master-docs][salt-master-docs] | [full][salt-full] |
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

| Image: | [common][salt-common] | [minion][salt-minion] | [master-mini][salt-master-mini] | [syndic][salt-syndic] | [master][salt-master] | [master-docs][salt-master-docs] | [full][salt-full] |
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

| Image: | [common][salt-common] | [minion][salt-minion] | [master-mini][salt-master-mini] | [syndic][salt-syndic] | [master][salt-master] | [master-docs][salt-master-docs] | [full][salt-full] |
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

[salt-common]: https://hub.docker.com/r/jarfil/salt-common
[salt-minion]: [salt-minion]
[salt-master-mini]: [salt-master-mini]
[salt-syndic]: [salt-syndic]
[salt-master]: [salt-master]
[salt-master-docs]: [salt-master-docs]
[salt-full]: [salt-full]
