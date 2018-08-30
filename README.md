# Vagrant CentOS 6 GUI

I am surprised that there isn't a ready to use vagrant box or how to setup an virtual machine (VM) of CentOS 6 with GUI without manual steps, but it looks like it's not pretty hard. Therefore, I create one and want to share with people with similar need.

## Features

- Ready-to-use
- Powered by [Vagrant](https://www.vagrantup.com/) to start a new CentOS 6 VM in [Virtual Box](https://www.virtualbox.org/)
- With Virtual Box [Guest Additions](https://www.virtualbox.org/manual/ch04.html) support


## Prerequisite

- [Vagrant](https://www.vagrantup.com/)
- [Virtual Box](https://www.virtualbox.org/)

## Installation

- Install [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) vagrant plugin:

  `vagrant plugin install vagrant-vbguest`

- Build the vagrant box

  ``` shell
    git clone https://github.com/hsiaoyi0504/vagrant_centos_6_gui
    cd vagrant_centos_6_gui
    vagrant up
  ```

- You are done ! Wait for VM restart and you can login CentOS through **vagrant** user with password **vagrant**.  