# centos6.5-php-ansible
Nginx, PHP-FPM, PostgreSQL provisioning for CentOS 6.5 using Ansible

To provision your machine, change or add your host file (currently _local_), and your variables in grooup_vars then run:
```
ansible-playbook -i local site.yml
```

If using vagrant, run the following command:
```
ansible-playbook -i local --private-key=~/.vagrant.d/insecure_private_key site.yml
```
