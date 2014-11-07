# Installing Ansible

The best way to get Ansible for Ubuntu is to add the project's PPA (personal package archive) to your system.

To do this effectively, we need to install the python-software-properties package, which will give us the ability to work with PPAs easily:
```
sudo apt-get update
sudo apt-get install python-software-properties
```

Once the package is installed, we can add the Ansible PPA by typing the following command:
```
sudo add-apt-repository ppa:rquillo/ansible
```

Press ENTER to accept the PPA addition.

Next, we need to refresh our system's package index so that it is aware of the packages available in the PPA. Afterwards, we can install the software:
```
sudo apt-get update
sudo apt-get install ansible
```

We now have all of the software required to administer our servers through Ansible.
