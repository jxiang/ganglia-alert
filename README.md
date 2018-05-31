ganglia-alert
=============

Initial commit is copied from https://code.google.com/p/ganglia-alert

## Instruction

To set up ganglia alerts, follow these steps:

1. Put gangalia-alert /usr/sbin
2. Rename the proper init.d file based on your platform
to ganglia-alert and put it under /etc/init.d
3. Create a configuration file ganglia-alert.conf, and
put it unser /etc/ganglia. For the syntax of configuration
file, check "ganglia-alert --help"
4. Now you can start/stop the alert service, and check
its status
