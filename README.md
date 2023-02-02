## self-hosted-apps-templates

- Directory `./self-hosted-apps/compose_templates` contains the docker-compose templates for usage. All of them are open source and can be self-hosted on a cheap single board computer like Raspberry pi.


 # TODOS

 - [x] Implement dynamic traefik configuarion for all services like (nextcloud & bitwarden).
 - [x] Implement Ansible Playbook to check server updates.
 - [ ] Setup authelia for extra layer of protection.
 - [ ] Homeserver backup solution (NFS or softrware RAID etc.)
 - [x] Automate (pihole domains update with ansible playbook) 
 - [ ] Implement proxy and tor and dns requests over (proxy is implemented but dns requests over tor takes time thats why will not do.)
 - [x] Found out the solution about codeserver not running with treafik
