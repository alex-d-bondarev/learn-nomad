# learn-nomad
Learn nomad basics

## Setup

Here nomad is configured to run inside VM. 
This VM is managed by Vagrant.

### Start VM

1. Install [virtualbox](https://www.virtualbox.org/)
1. Install [vagrant](https://www.vagrantup.com/downloads).  
1. In the shell run:
```bash
vagrant up
vagrant ssh
# Do some fun, like running 'nomad'
logout
# Suspending the virtual machine will stop it and 
# save its current running state
vagrant suspend
# Halting the virtual machine will gracefully shut down 
# the guest operating system and power down the guest machine
vagrant halt
```

### Update VM

After updates in Vagrantfile you need to reload VM like: 
```bash
vagrant reload
```

### Clean up everything

```bash
vagrant destroy
vagrant box list
vagrant box remove <box from previous command>
```

## Nomad UI

http://localhost:4646/
