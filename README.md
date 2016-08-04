# jekyll-vagrant-dev

Quickly have a virtual machine up and running, serving a Jekyll and webserver instance for you, without changing your base system or being limited by it.
The virtual machine will run in the background, process your changes to the source and presenting the results on your hosts [`http://localhost:4000`](http://localhost:4000).

You need to have [VirtualBox](https://www.virtualbox.org) and [Vagrant](https://www.vagrantup.com/downloads.html) installed.

Put the `Vagrantfile` alongside your jekyll files. After that, it's as easy as:

```shell
/path-to/openhab-docs$ vagrant up
```
