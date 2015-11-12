The following steps shows how you can spin up a Virtual Machine for tool SketchLink :

-> Install vagrant and virtualbox on your host machine.
-> Download the Vagrantfile from build-vm folder on your machine and save it in a folder where you want to install the VM.
-> From the host, navigate to that folder and execute the command : "vagrant up"

Note :

1. The Virtual Machine will boot up quickly and but the "vagrant up" command runs for nearly half an hour to complete as it provisions the VM for use when ran for the first time.
2. Deploys Base Vagrant Box : Ubuntu 14.04 Desktop
3. Default VM Login Credentials:
    user: vagrant
    password: vagrant

References :

A vagrant tutorial can be found [here](https://docs.vagrantup.com/v2/getting-started/index.html)
The binaries for vagrant can be found [here](https://www.vagrantup.com/downloads.html)
Vagrant tutotial by Dustin Barnes,Vagrant Tutorial

