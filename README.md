### Install one specific or more Php versions

##### Usage
```
- name: Php multiversion
  hosts: all
  become: yes
  roles:
    - { role: purplenetwork.php, php_version: '5.5' }
    - { role: purplenetwork.php, php_version: '5.6' }
    - { role: purplenetwork.php, php_version: '7.0' }
    - { role: purplenetwork.php, php_version: '7.1' }
```    