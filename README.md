Install
=======

From a VM, checkout this repository and type

```
sudo apt-get install ansible
ansible-galaxy install -f -r requirements.yml
ansible-playbook -i "localhost," -c local main.yml
```

