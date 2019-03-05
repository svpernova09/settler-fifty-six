# Settler Fifty Six

The scripts that build the Homestead Fifty Six development environment. 

> The Settler Fifty Six Project is built on top of and extends much of the [Laravel Settler project](https://github.com/laravel/settler). 

## Usage

You probably don't want this repo, follow instructions at https://laravel.com/docs/homestead instead.

If you know what you are doing:

* Clone [chef/bento](https://github.com/chef/bento) into same top level folder as this repo.
* Run `./bin/copy-to-bento.sh`
* Replace `scripts/cleanup.sh` with `scripts/homestead.sh` in file `ubuntu/ubuntu-18.04-amd64.json`
* Follow normal [Packer](https://www.packer.io/) practice of building `ubuntu/ubuntu-18.04-amd64.json`
