# learn-nomad
Learn nomad basics

## Start virtual env

1. Install [virtualbox](https://www.virtualbox.org/)
1. Install [vagrant](https://www.vagrantup.com/downloads).  
1. In shell run:
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

## Clean up everything

```bash
vagrant destroy
vagrant box list
vagrant box remove <box from previous command>
```
