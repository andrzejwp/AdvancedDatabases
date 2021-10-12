# AdvancedDatabases

## Preparing the environment

We will be using Linux during the classes, so unless you already have it installed - please follow the steps to prepare a virtual machine for the purpose of the lab:
1. Download [Virtualbox]() and install this virtualization software on your computers.
2. Download a pre-installed virtual harddrive with Ubuntu 21.04 from [OSBoxes](https://osboxes.org/ubuntu) website.
3. Unzip the downloaded file (it's a .7z archive, the disk is in the archive)
4. Start Virtualbox
5. Create a new Virtual Machine, call it Ubuntu 21.04 and assign min. 2 GB of RAM and 2 VCPUs (recommended 4GB + 2 VCPU)
6. Add the downloaded harddrive to the machine
7. Start the machine
8. Login using the credentials: Username – osboxes, Password – osboxes.org

Once you log in use the following commands to install the required software:
```
sudo apt-get -y install mysql-server
```

Next - download MySQL Workbench from [this website](https://dev.mysql.com/downloads/workbench/)
In the terminal proceed to the Downloads folder and install the downloaded package with the command:
```
sudo dpkg -i mysql-workbench*.deb
```

Finally - please download the Sakila database from [this website](https://dev.mysql.com/doc/index-other.html)
