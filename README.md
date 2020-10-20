# vorteil-splunk

## Description

This is the public repo used to create the Medium article:

https://medium.com/@wilhelm.wonigkeit/splunk-without-an-os-just-vorteil-7abaaf456d79

This package contains the Vorteil configuration files, libraries and some shell commands needed for Splunk and the "splunk start" command. The package DOES NOT contain the Splunk binaries or tarballs. This would need to be downloaded from the Splunk website:

![alt text](relative/path/to/img.jpg?raw=true "Title")

## Using the Vorteil machine configuration

1. Install the Vorteil Studio
2. Clone the repo to an appropriate directory on your local machine
3. Unzip the Splunk tarball to the /opt/ directory
4. Copy the user-seed.conf file in the root directory of the repo to /opt/splunk/etc/system/local/user-seed.conf
5. Run the machine using "vorteil run"

If you have any questions just ask!
