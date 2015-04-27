# Ansible Playbooks

Example playbooks. I used these to setup my various computers.

## Usage

See .travis.yml for Debian based command examples.

1. Install pip & Ansible
2. Install dependencies `ansible-galaxy install -r .requirements.yml`
3. Create file `inventory` with groups
4. Run `ansible-playbook -i inventory THE_PLAYBOOK.yml` 
  - On Elementary OS run `ansible-playbook -i inventory THE_PLAYBOOK.yml --extra-vars "ansible_os_family=Debian ansible_distribution=ubuntu"`
  - This is because a lot of re-used playbooks include Debian and Ubuntu vars

## Playbooks

### Clients

#### client.desktop

- [ ] administration (bash, byobu, tree, etc)
- [ ] backup (rsync, scripts)
- [ ] file shares (autoFS)
- [ ] UI fixes (Elementary OS Plank, MacOSX bad edid, etc)
- [ ] web browser (Google Chrome)

#### client.developer.ansible

- [ ] scm (SmartGit)
- [ ] editor (SublimeText, PackageControl, PackageControl - Ansible Syntax)
- [ ] web browser (Google Chrome)

#### client.openElec

- [ ] file shares (autoFS)
- [ ] XBMC

### Servers

#### server.file

- [X] hard-drive mounts
- [X] bind mounts
- [X] *nix shares (nfs)
- [ ] administration (bash, byobu, tree, etc)
- [ ] nfs authentication
- [ ] windows shares (samba)

#### server.media

- [ ] administration (bash, byobu, tree, etc)
- [ ] XBMC (mySQL, database)

#### server.router 

- [X] WAN/LAN (interfaces)
- [X] DHCP/DNS (dnsmasq)
- [X] firewall (FireHOL)
- [ ] administration (bash, byobu, tree, etc)
- [ ] management (dnsmasq DHCP options)
- [ ] monitoring (Monit)
- [ ] exposure (Open-vpn)

#### server.torrent 

- [X] torrenting (rTorrent)
- [X] web interface (nginx, php, ruTorrent)
- [ ] administration (bash, byobu, tree, etc)
- [ ] file management (JRE  1.8, FileBot)
- [ ] enhance web interface (ruTorrent plugins)

## System

### Servers 

1. Ubuntu Server 14.04.2

### Clients 

1. elementary os
2. Mac OS X 

## Author

Prescott Chris
