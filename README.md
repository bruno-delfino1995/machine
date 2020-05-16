# Machine Setup

> Machine setup powered by [Ansible](https://www.ansible.com/), heavily inspired
by [caarlos0/machine](https://github.com/caarlos0/machine)

## Usage

This is supposed to be run after a [clean install](./Installation.md) of [Arch Linux](https://www.archlinux.org/) with some dependencies installed. If there's a missing dependency you'll be properly instructed on how to install it.

You can clone this repository and run `./setup`, but if desired you can ditch git and use the zip file provided by GitHub. It's up to you whether you want to install `zip` or `git`, IMHO, it's more worthy to use git because you get the updates more easily, anyway, if you want to skip git just run the following steps:

```bash
wget https://github.com/bruno-delfino1995/machine/archive/master.zip
unzip master.zip
cd machine-master
```

Once the code is downloaded and you're in the correct directory, just run `./setup`, it'll install all the applications and tools that I use for development on a daily basis, and of course, some customizations that I've done.
