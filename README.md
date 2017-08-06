# vagrant
Vagrant resources and explanations

## Install vagrant and virtualBox
```
sudo apt-get install virtualbox
sudo apt-get install vagrant
```
## Check virtual machine Images

https://app.vagrantup.com/boxes/search?_ga=

https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/

http://www.vagrantbox.es/

## Vagrant commands

- List available boxes
```
vagrant box list
```
- Add box from repository
```
vagrant box add ubuntu/trusty64
```
- Create vagrant configration file
```
vagrant init
```
##### Note: Configuration file has the name 'Vagranfile'
- Run virtual machine
```
vagrant up
```
- Enter to the virtual machine
```
vagran ssh
```
- Close virtual machine
```
halt
```
- Destroy virtual machine
```
vagrant destroy
```
- Run provisioning scripts
```
vagrant provision
```
- Run configuration file and power up virtual machine
```
vagrant reload
```
