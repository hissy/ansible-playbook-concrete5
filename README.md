# Ansible Playbook: Create concrete5 site on EC2 instance

* Launch an ec2 instance with specific tag
* Install and setup nginx
* Install and setup php71
* Install git
* Install composer
* Install and setup mariadb
* Install concrete5

## Install requirements

```bash
$ ansible-galaxy install -r requirements.yml
```