Description
===========

This will setup a PC with all the required tools to automatically fetch and download torrents.

It includes:
 - VPN connection through https://www.privateinternetaccess.com
 - Download torrents through transmission web daemon
 - Fetch the torrents from an rss feed through flexget

Install
=======

From a VM, checkout this repository and type

```
sudo apt-get install ansible
ansible-galaxy install -f -r requirements.yml
ansible-playbook -i "localhost," -c local main.yml -e username=vpn_user_name -e password=vpn_user_password -e flexget_conf_url=http://flexget_configuration_rul
```

