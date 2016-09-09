# Picladies
picladies website and mobile app

## Requirements:

Download the latest version of VirtualBox by Oracle:

https://www.virtualbox.org/wiki/Downloads

Install Ansible (minimum version: 2.0):

https://www.ansible.com/

Install vagrant on your host machine:

http://www.vagrantup.com/

You may want to get familiar with VirtualBox (install a box, play around for
a bit) and Vagrant before continuing
to be familiar with the virtual development environment.

## Installation (On the host machine):

Clone the code from WattzOn github repository:

```
$ git clone https://github.com/emiviada/picladies.git
```

Change to picladies directory

```
$ cd picladies
```

Run composer install under the /admin folder to install php dependencies:

```
$ composer install
```

Provision the box:

```
$ vagrant up --provision
```