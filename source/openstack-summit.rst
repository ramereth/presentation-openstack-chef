Deploying and Managing OpenStack with Chef
==========================================

Lance Albertson
OSU Open Source Lab

Installing OpenStack is like herding cats
=========================================

* Lots of services, package dependencies and moving parts!
* Several methods to install and manage OpenStack

Chef to the rescue!
===================

* Why Chef? Because we like it and use it everywhere so Chef all the things!
* Stackforge: Over a dozen community cookbooks
* So many moving parts, difficult to see what is really needed

Wrapper cookbook and roles
==========================

* Created a wrapper cookbook osl-openstack
* Provides a way for us to manage site specific configuration
* Too many roles!
* We also created our own roles

Test Kitchen
============

* Powerful tool for testing cookbooks
* Integration testing on crack!
* Uses Vagrant by default
* Testing OpenStack on OpenStack

Packer
======

* Cloud image creation tool
* Unifies building of images across multiple platforms
* Bento: Chef repo full of packer scripts
* OSL Forked Bento: OpenStack (kvm) packer scripts
