# NTPD

NTP service.

## Software

Chrony is used for the NTP service.
See https://chrony.tuxfamily.org/documentation.html

## Coniguration

Configuration file chrony.conf is in the ./files subfolder
An ansible task will copy it in the the ntpd image during the docker build proces.
Check the chrony site on how to use the configuration file.

## update chrony configuration

To change the configuration for chrony. Do the following.
1. Update the chrony.conf file
2. from the playbooks folder (contains all the ansible playbooks file) run <br>```ansible-playbook playbook-ntpd.yaml --tags build``` to build the image<br>or run<br>```ansible-playbook playbook-ntpd.yaml --tags run``` to build the docker image and run the ntpd container.
