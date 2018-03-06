# Vagrantfile for WSO2 IoT Server

This section defines the procedure to run Vagrant resources of the WSO2 IoT Server.

Please note that in order to run these Vagrant resources, you need to install
[Oracle VM VirtualBox](http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html),
as Vagrant uses Oracle VM VirtualBox as the default provider.

Virtualization should be enabled in BIOS settings before building the boxes.

**Following are the WSO2 IoT Server profiles**

  1. IoT Server
  2. Broker
  3. Analytics

## How to run the Vagrantfile

1. Checkout this repository into your local machine using the following Git command.

```
    git clone https://github.com/wso2/vagrant-iot.git
```

2. Move to `vagrant-iot` folder.

```
    cd vagrant-iot
```

3. Spawn up the Vagrant setup

```
    vagrant up
```

4. Access the status device management console via the given URL

```
    https://172.28.128.5:9443/devicemgt
```
