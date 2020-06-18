Provisioning a new site
=======================

## Required packages:

* nginx
* python3.6
* virtualenv + pip
* Git

eg, on Ubuntu:

    sudo apt-get install software-properties-common
    sudo add-apt-repository ppa:fkrull/deadsnakes
    sudo apt-get install python3.6 python3.6-venv
    
## Nginx Virtual Host config

* see nginx.template.conf
* replace SITENAME with e.g., staging.my-domain.com

## Systemd service

* see gunicorn-systemd.template.service
* replace SITENAME with, e.g., staging.my-domain.com

## Folder structure:
Assume we have a user account at /home/username
```
/home/username
|__sites
    |__SITENAME
        |__database
        |__source
        |__static
        |__virtualenv
```