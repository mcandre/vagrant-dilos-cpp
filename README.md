# vagrant-dilos-cpp: a Vagrant box for building C/C++ binaries for Solaris/Illumos (DilOS)

# VAGRANT CLOUD

https://app.vagrantup.com/mcandre/boxes/vagrant-dilos-cpp

# EXAMPLE

```console
$ vagrant up
$ vagrant ssh -c "cd /vagrant && g++ -o hello hello.cpp && ./hello"
Hello World!
```

# RUNTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider

# BUILDTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider
* [make](https://www.gnu.org/software/make/)

# EXPORT

```console
$ make vagrant-dilos-cpp.box
```
