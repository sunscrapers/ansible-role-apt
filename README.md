# Ansible APT role

Ansible APT role ensures that apt cache is up to date and sets up unattended updates. It also installs the given list 
of apt packages.

Developed by [SUNSCRAPERS](http://sunscrapers.com/) with passion & patience.

## Installation

```
$ ansible-galaxy install sunscrapers.apt -p roles/
```

## Customization

To customize the role you can override the following default variables:

```yaml
apt_cache_valid_time: 3600
apt_install_packages: []
apt_setup_unattended_upgrades: yes
```
