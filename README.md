# vagrant-dilos-cpp: a Vagrant box for building C/C++ binaries for Solaris/Illumos (DilOS)

# VAGRANT CLOUD

https://app.vagrantup.com/mcandre/boxes/vagrant-dilos-cpp

# EXAMPLE

```console
$ vagrant up
$ vagrant ssh -c "cd /vagrant && g++ -o hello hello.cpp && ./hello"
Hello World!
```

# REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* A VM provider, such as [VirtualBox](https://www.virtualbox.org), [VMware](https://www.vmware.com), or [libvirt](https://libvirt.org)

# EXPORT

```console
$ vagrant destroy -f; vagrant up && vagrant package --output vagrant-dilos-cpp.box
```
