# ansibletesting
git repo for testing stuff with ansible

---
getReadyforAnsible.yml
 - playbook, that runs as root, sets up ansible user, and copies over its authorized_keys file

getReadyforAnsible-v2.yml
 - playbook, that runs as root, sets up ansible user, and copies over its authorized_keys file
  - user_name and user_pass is in encrypted vault file "vars/vars-file.yml".
