# vagrant-hashicorp

* https://learn.hashicorp.com/tutorials/vagrant/getting-started-index
```

vagrant init hashicorp/bionic64

vagrant up

vagrant destroy

```

# openstack
```
vagrant init najoy/os-pike-aio --box-version 1.0.0

vagrant box add najoy/os-pike-aio

vagrant up controller
Bringing machine 'controller' up with 'virtualbox' provider...
==> controller: Importing base box 'najoy/os-pike-aio'...
==> controller: Matching MAC address for NAT networking...
==> controller: Checking if box 'najoy/os-pike-aio' version '1.0.0' is up to date...
==> controller: Setting the name of the VM: controller
==> controller: Clearing any previously set network interfaces...
==> controller: Available bridged network interfaces:
1) en0: Wi-Fi (Wireless)
2) en5: USB Ethernet(?)
3) en3: 3 Thunderbolt
4) en4: 4 Thunderbolt
5) en1: 1 Thunderbolt
6) en2: 2 Thunderbolt
7) bridge0
8) p2p0
9) awdl0
10) llw0
==> controller: When choosing an interface, it is usually the one that is
==> controller: being used to connect to the internet.

vagrant status
vagrant halt
vagrant up

```
