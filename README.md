# Load balanced vagrant setup with NGINX and PHP-FPM.

### Getting started

```
vagrant up
ansible-playbook ansible/playbook.yml --inventory-file ansible/inventories/dev
open http://192.168.30.21/
```
