# Salt docker images

## Supported tags

* `latest`, `debian`, `debian-stretch`
* **TODO:** `fedora`, `fedora-23`

Debian Stretch images: [![](https://imagelayers.io/badge/jarfil/salt-full:debian-stretch.svg)](https://imagelayers.io/?images=jarfil%2Fsalt-common:debian-stretch,jarfil%2Fsalt-minion:debian-stretch,jarfil%2Fsalt-master-mini:debian-stretch,jarfil%2Fsalt-syndic:debian-stretch,jarfil%2Fsalt-master:debian-stretch,jarfil%2Fsalt-master-docs:debian-stretch,jarfil%2Fsalt-full:debian-stretch 'Get your own badge on imagelayers.io')
Fedora images: **(TODO)**

## Debian Stretch

| Image: | common | minion | master-mini | syndic | master | master-docs | full |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| FROM: | debian | common | common | master-mini | master-mini | master | master-docs |
| **Packages** |
| salt-common | + | + | + | + | + | + | + |
| salt-minion |  | ++ |  |  | ++ | + | + |
| salt-master |  |  | ++ | + | + | + | + |
| salt-ssh |  |  |  |  | ++ | + | + |
| salt-cloud |  |  |  |  | ++ | + | + |
| salt-syndic |  |  |  | ++ |  |  | ++ |
| salt-api |  |  |  |  |  |  | ++ |
| salt-proxy |  |  |  |  |  |  | ++ |
| man |  |  |  |  |  | ++ | + |
| less |  |  |  |  |  | ++ | + |
| salt-doc |  |  |  |  |  | ++ | + |
| **Autostart** |
| minion |  | + |  |  | + | + |  |
| master |  |  | + | + | + | + | + |
| syndic |  |  |  | + |  |  |  |  |

| Image | Layers |
| --- | --- |
| salt-common | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-stretch.svg)](http://microbadger.com/#/images/jarfil/salt-common:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-minion | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-stretch.svg)](http://microbadger.com/#/images/jarfil/salt-minion:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-master-mini | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-stretch.svg)](http://microbadger.com/#/images/jarfil/salt-master-mini:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-syndic | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-stretch.svg)](http://microbadger.com/#/images/jarfil/salt-syndic:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-master | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-stretch.svg)](http://microbadger.com/#/images/jarfil/salt-master:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-master-docs | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-stretch.svg)](http://microbadger.com/#/images/jarfil/salt-master-docs:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-full | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-stretch.svg)](http://microbadger.com/#/images/jarfil/salt-full:debian-stretch 'Get your own badge on imagelayers.io') |
