# Ansible Playbooks

My playbooks I use to configure my computers. Server playbooks intended for apt-based OS. Client playbooks intended for
apt-based OS & Mac OS X.

## Usage

See .travis.yml for examples of installating requirements and usage.

## Playbooks

### client.desktop

- [ ] backup (rsync, scripts)
- [ ] file shares (autoFS)
- [ ] UI fixes (Elementary OS Plank, MacOSX bad edid, etc)
- [ ] web browser (Google Chrome)

### client.developer

- [ ] administration (bash, byobu, tree, etc)
- [ ] scm (SmartGit)
- [ ] editor (SublimeText, SublimeText PackageControl)

### client.media

- [X] media playback (Kodi)
- [ ] TV playback (tuner, tvheadend, mc2xml)

### server.media

- [X] administration (bash, byobu, tree, etc)
- [X] hard-drive mounts
- [X] bind mounts
- [X] linux shares (nfs)
- [X] Kodi (mySQL db)
- [ ] nfs authentication
- [ ] windows shares (samba)

### server.router 

- [X] administration (bash, byobu, tree, etc)
- [X] WAN/LAN (interfaces)
- [X] DHCP/DNS (dnsmasq)
- [X] firewall (FireHOL)
- [ ] management (dnsmasq DHCP options)
- [ ] monitoring (Monit)
- [ ] exposure (Open-vpn)

### server.torrent 

- [X] administration (bash, byobu, tree, etc)
- [X] torrenting (rTorrent)
- [X] web interface (nginx, php, ruTorrent)
- [X] file management (JRE  1.8, FileBot)
- [ ] enhance web interface (ruTorrent plugins)

## Author

Prescott Chris
