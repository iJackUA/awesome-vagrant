# Awesome Vagrant

A curated list of awesome Vagrant resources, plugins, tutorials and other nice things.
Inspired by [awesome lists](https://github.com/sindresorhus/awesome).


## Official resources

* [Vagrant site](http://www.vagrantup.com/) - installation instruction, official manuals and docs.
* [GitHub repo](https://github.com/mitchellh/vagrant) - source code, issues discussion and collaboration.
* [Vagrant Cloud](https://vagrantcloud.com/) - config share, boxes distribution and discovery (also premium features of private collaboration and sharing).


## Boxes

*Where to find OS boxes ?*

* [Vagrantbox.es](http://www.vagrantbox.es/) - the biggest list of all available boxes, maintained by community via GitHub pull requests.
* [Vagrant Cloud](https://vagrantcloud.com/discover/featured) - see [above](#official-resources)
* [Cloud Images Ubuntu.com](https://cloud-images.ubuntu.com/vagrant/) - "clean" official Ubuntu cloud images.
* [Baseboxes from Opscode](https://github.com/opscode/bento#current-baseboxes) - CentOS, Fedora, Debian, FreeBSD, Ubuntu.
* [Puppet Labs Vagrant Boxes](http://puppet-vagrant-boxes.puppetlabs.com/) - these boxes are provided to be used by various Puppet projects.
* [Windows Box](http://vagrantbox.msopentech.com/) - evaluation version of Windows, packaged as a Vagrant Box for Hyper-V.


## Provisioning

* [All available build in provisioning providers](https://docs.vagrantup.com/v2/provisioning/index.html) - official doc
* [Vaprobash](http://fideloper.github.io/Vaprobash/index.html) - Vagrant Provisioning Bash Scripts


## Notable plugins

*You can install these modules by this command `vagrant plugin install MODULE-NAME`*

* [List of available Vagrant plugins from GitHub wiki](https://github.com/mitchellh/vagrant/wiki/Available-Vagrant-Plugins)
* [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) - autoupdate VirtualBox guest additions (according to VB version)
* [vagrant-hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater) - adds an entry to your /etc/hosts file on the host system
* [vagrant-cachier](http://fgrehm.viewdocs.io/vagrant-cachier) - share a common package (apt-get, npm, etc.) cache among similiar VM instances.
* [vagrant-host-shell](https://github.com/phinze/vagrant-host-shell) - a vagrant provisioner to run commands on the host when a VM boots.
* [vagrant-ansible-local](https://github.com/jaugustin/vagrant-ansible-local)  allow provisioning your VM with ansible playbooks directly from the guest VM
* [sahara](https://github.com/jedi4ever/sahara) - easy manage VM state (commit/rollback while experimenting with software stack)


## Helpers / Tools

* [Packer](http://www.packer.io/) - a tool for creating identical machine images for multiple platforms from a single source configuration. For fast infrastructure deployment with multi-provider portability.
* [Veewee](https://github.com/jedi4ever/veewee) - a tool for easily (and repeatedly) building custom Vagrant base boxes, KVMs, and virtual machine images.
* [Vagrant plugin for ZSH shell](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#vagrant) - auto-complete for commands, task names, box names and built-in documentation


## Web services

*To generate Vagrantfile with automated provisioning scripts.*

* [Phansible](http://phansible.com/) - provides an easy to use interface that helps you generate Ansible Playbooks for PHP based projects.
* [PuPHPet](https://puphpet.com/) - a simple GUI to set up virtual machines for <s>PHP</s> Web development.
* [Protobox](http://getprotobox.com/) - PuPHPet analog, but uses own installer with YAML configuration format to controls everything that is installed on the virtual machine.
* [Rove](http://rove.io/) - a service that allows you to pregenerate typical Vagrant builds.

## Proxy services

*To proxy your local web server and make it publicly available over the internet.*

* [xip.io](http://xip.io) - a magic domain name that provides wildcard DNS
for any IP address.
* [proxylocal.com](http://proxylocal.com) - proxy your local web-server and make it publicly available over the internet.
* [localtunnel.me](http://localtunnel.me) - assign you a unique publicly accessible url that will proxy all requests to your locally running webserver.

## Tutorials

* [Getting Started With Vagrant](http://www.thisprogrammingthing.com/2013/getting-started-with-vagrant/) by This Programming Thing
* [Getting started with Vagrant - automated dev servers deploy and provisioning.](http://stdout.in/en/post/getting_started_with_vagrant_automated_dev_servers_deploy_and_provisioning)
* [Working with Advanced Vagrant features in PhpStorm.](http://confluence.jetbrains.com/display/PhpStorm/Working+with+Advanced+Vagrant+features+in+PhpStorm)
* [Sharing Your Virtual Machine on the Web with Vagrant Share](http://scotch.io/tutorials/sharing-your-virtual-machine-on-the-web-with-vagrant-share)

## Books

* [Vagrant: Up and Running](http://www.amazon.com/gp/product/1449335837) by Mitchell Hashimoto.
* [Vagrant CookBook](https://leanpub.com/vagrantcookbook) by Erika Heidi

## Popular readymade environments

* [Vagrantpress](http://vagrantpress.org/) - development enviroment for creating and modifying WordPress sites.
* [Joomla-Vagrant](https://github.com/joomlatools/joomla-vagrant)
* [VDD](https://www.drupal.org/project/vdd) - Vagrant Drupal Development.
* [Try Yii2](https://github.com/iJackUA/try-yii2) - try Yii2 with Vagrant VM + Ansible provisioning = Complete readymade virtual server playground
* [Laravel4-Vagrant](https://github.com/bryannielsen/Laravel4-Vagrant) - run Laravel 4 inside a Ubuntu 12.04 Vagrant Virtual Machine w/PHP 5.5.
* [OpenStack on Ansible with Vagrant](https://github.com/openstack-ansible/openstack-ansible)
