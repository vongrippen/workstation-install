Workstation Install
===================

A simple ansible playbook for quickly bootstrapping a dev machine from scratch

Currently works/tested on:

* Ubuntu 14.04
* Mac OS X 10.10

Mac OS X Installation
---------------------
  xcode-select --install
  sudo easy_install pip
  sudo pip install ansible

Ubuntu Installation
-------------------
  apt-get install ansible

Run the Playbook
----------------
  ansible-playbook -K -i inventory playbook.yml
