## self-hosted-apps-templates

- Directory `./self-hosted-apps/compose_templates` contains the docker-compose templates for usage. All of them are open source and can be self-hosted on a cheap single board computer like Raspberry pi.

## List of apps

<p align="left"> 
  <a href="https://pi-hole.net/" target="_blank"> <img src="https://raw.githubusercontent.com/pi-hole/docs/master/docs/images/logo.svg" alt="python" width="80" height="80"/> </a> 
  <a href="https://nextcloud.com/" target="_blank"> <img src="https://raw.githubusercontent.com/nextcloud/nextcloud.com/master/assets/img/logo/logo_nextcloud_blue.svg" alt="ansible" width="80" height="80"/> </a> 
  <a href="https://www.portainer.io/" target="_blank"> <img src="https://raw.githubusercontent.com/portainer/portainer/develop/app/assets/ico/favicon.ico" alt="docker" width="80" height="80"/> </a> 
</p>

more coming soon....

 ## TODOS

 - [x] Implement dynamic traefik configuarion for all services like (nextcloud & bitwarden).
 - [x] Implement Ansible Playbook to check server updates.
 - [ ] Setup authelia for extra layer of protection.
 - [ ] Homeserver backup solution (NFS or softrware RAID etc.)
 - [x] Automate (pihole domains update with ansible playbook) 
 - [ ] Implement proxy and tor and dns requests over (proxy is implemented but dns requests over tor takes time thats why will not do.)
 - [x] Found out the solution about codeserver not running with treafik
