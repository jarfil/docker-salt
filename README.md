# Salt docker images

## Supported tags

* `latest`, `debian`, `debian-stretch`
* **TODO:** `fedora`, `fedora-23`

Debian Stretch images: [![](https://imagelayers.io/badge/jarfil/salt-full:debian-stretch.svg)](https://imagelayers.io/?images=jarfil%2Fsalt-common:debian-stretch,jarfil%2Fsalt-minion:debian-stretch,jarfil%2Fsalt-master-mini:debian-stretch,jarfil%2Fsalt-syndic:debian-stretch,jarfil%2Fsalt-master:debian-stretch,jarfil%2Fsalt-master-docs:debian-stretch,jarfil%2Fsalt-full:debian-stretch 'Get your own badge on imagelayers.io')
Fedora images: **(TODO)**

## Debian Stretch

|  | common | minion | master-mini | syndic | master | master-docs | full |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **FROM** | debian | common | common | master-mini | master-mini | master | master-docs |
| salt-common | + | + | + | + | + | + | + |
| salt-minion |  | ++ |  |  | ++ | + | + |
| salt-master |  |  | ++ | + | + | + | + |
| salt-ssh |  |  |  |  | ++ | + | + |
| salt-cloud |  |  |  |  | ++ | + | + |
| salt-syndic |  |  |  | ++ |  |  | ++ |
| man |  |  |  |  |  | ++ | + |
| less |  |  |  |  |  | ++ | + |
| salt-doc |  |  |  |  |  | ++ | + |
| **Autostart** |  |  |  |  |  |  |  |
| minion |  | + |  |  | + | + |  |
| master |  |  | + | + | + | + | + |
| syndic |  |  |  | + |  |  |  |  |

| Image | Layers |
| --- | --- |
| salt-common | [![](https://imagelayers.io/badge/jarfil/salt-common:debian-stretch.svg)](https://imagelayers.io/?images=jarfil/salt-common:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-minion | [![](https://imagelayers.io/badge/jarfil/salt-minion:debian-stretch.svg)](https://imagelayers.io/?images=jarfil/salt-minion:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-master-mini | [![](https://imagelayers.io/badge/jarfil/salt-master-mini:debian-stretch.svg)](https://imagelayers.io/?images=jarfil/salt-master-mini:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-syndic | [![](https://imagelayers.io/badge/jarfil/salt-syndic:debian-stretch.svg)](https://imagelayers.io/?images=jarfil/salt-syndic:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-master | [![](https://imagelayers.io/badge/jarfil/salt-master:debian-stretch.svg)](https://imagelayers.io/?images=jarfil/salt-master:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-master-docs | [![](https://imagelayers.io/badge/jarfil/salt-master-docs:debian-stretch.svg)](https://imagelayers.io/?images=jarfil/salt-master-docs:debian-stretch 'Get your own badge on imagelayers.io') |
| salt-full | [![](https://imagelayers.io/badge/jarfil/salt-full:debian-stretch.svg)](https://imagelayers.io/?images=jarfil/salt-full:debian-stretch 'Get your own badge on imagelayers.io') |
