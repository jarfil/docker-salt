# Salt docker images

## Supported tags

* `latest`, `debian`, `debian-stretch`
* `testing`, `debian-buster`
* **TODO:** `debian-unstable`
* **TODO:** `fedora`, `fedora-23`

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
| salt-common | [![](https://images.microbadger.com/badges/image/jarfil/salt-common:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-common:debian-stretch "Get your own image badge on microbadger.com") |
| salt-minion | [![](https://images.microbadger.com/badges/image/jarfil/salt-minion:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-minion:debian-stretch "Get your own image badge on microbadger.com") |
| salt-master-mini | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-mini:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master-mini:debian-stretch "Get your own image badge on microbadger.com") |
| salt-syndic | [![](https://images.microbadger.com/badges/image/jarfil/salt-syndic:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-syndic:debian-stretch "Get your own image badge on microbadger.com") |
| salt-master | [![](https://images.microbadger.com/badges/image/jarfil/salt-master:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master:debian-stretch "Get your own image badge on microbadger.com") |
| salt-master-docs | [![](https://images.microbadger.com/badges/image/jarfil/salt-master-docs:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-master-docs:debian-stretch "Get your own image badge on microbadger.com") |
| salt-full | [![](https://images.microbadger.com/badges/image/jarfil/salt-full:debian-stretch.svg)](http://microbadger.com/images/jarfil/salt-full:debian-stretch "Get your own image badge on microbadger.com") |
