# Vagrant Jenkins
### (Work in Progress - Not Fully Functional)

A Jenkins CI box, utilizing a Vagrant VM (default: Ubuntu 12.04 Precise Pangolin 32-bit) provisioned with Chef Solo.

## Dependencies

You must have the following dependencies installed to run this VM.

* [VirtualBox](https://www.virtualbox.org/)
* [Ruby](http://www.ruby-lang.org/en/)
    * [Librarian-Chef](https://github.com/applicationsonline/librarian-chef)
* [Vagrant](http://vagrantup.com/)
* [Vagrant Omnibus](https://github.com/schisamo/vagrant-omnibus)

## Chef Cookbooks included:

* [apt](https://github.com/opscode-cookbooks/git)
* [git](https://github.com/opscode-cookbooks/git)
* [jenkins](https://github.com/opscode-cookbooks/jenkins)

## Usage

Clone it. Run it.

```bash
$ git clone https://github.com/devert/vagrant-jenkins
$ vagrant plugin install vagrant-omnibus
$ gem install librarian-chef
$ librarian-chef install
$ vagrant up
```
