This is a updating script for debian/ubuntu-like systems. All it does is to take only the security updates and then run the apt-get upgrade itself.

# This script assumes you have already made that:
````
sudo grep "-security" /etc/apt/sources.list | sudo grep -v "#" > /etc/apt/security.sources.list
````
