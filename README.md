drupal8.dev
===========

Vagrant machine for drupal 8 (VirtualBox 4.3)

1.- Clone this repo
```bash
$ git clone https://github.com/hechoendrupal/drupal8.dev.git
$ cd drupal8.dev
$ vagrant up

```

2.- Add VM to hosts file
```bash
  192.168.9.10 drupal8.dev

```

3.- Clone Drupal 8 repo
```bash
$ vagrant ssh
$ cd /vagrant/www
$ git clone --branch 8.x http://git.drupal.org/project/drupal.git drupal8.dev

```

4.- Access and install Drupal 8 via http://drupal8.dev

#### Tools on vm
* composer
* drush for drupal 8
* xdebug
* vim

#### Database Credentials
* Name: drupal
* User: drupal
* Pass: drupal

#### Minimum requirements
* VirtualBox 4.3.x
* Vagrant 1.4.x
