# Vagrantfile for WSO2 IoT Server

In order to use Vagrant boxes, you will need an active subscription from WSO2 since the Vagrant boxes hosted at vagrant.wso2.com contains the latest updates and fixes to WSO2 IoT Server. You can sign up for a Free Trial Subscription [here](https://wso2.com/free-trial-subscription).

If you wish to use the Vagrant boxes without updates, please build them from [here](https://github.com/wso2/vagrant-boxes).

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
> If you are to try out an already released zip of this repo, please ignore this 1st step.


2. Move to `vagrant-iot` folder.

```
    cd vagrant-iot
```
>If you are to try out an already released zip of this repo, please ignore this 2nd step also. Instead, extract the zip file and directly browse to `vagrant-iot-<released-version>` folder.

>If you are to try out an already released tag, after executing 2nd step, checkout the relevant tag, i.e. for example: <br> git checkout tags/v3.3.0.1 and continue below steps.

3. Spawn up the Vagrant setup

```
    vagrant up
```

4. Access the API Publisher and Device Management via the URLs given below.

* Device Management
```
    https://localhost:9443/devicemgt
```

* APP Publisher

```
    https://localhost:9443/publisher
```

* Carbon

```
    https://localhost:9443/carbon
```
