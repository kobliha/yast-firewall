# YaST Firewall - Configures Firewalld #

[![Coverage
Status](https://coveralls.io/repos/github/yast/yast-firewall/badge.svg?branch=master)](https://coveralls.io/github/yast/yast-firewall?branch=master)
[![Travis Build](https://travis-ci.org/yast/yast-firewall.svg?branch=master)](https://travis-ci.org/yast/yast-firewall)
[![Jenkins Build](http://img.shields.io/jenkins/s/https/ci.opensuse.org/yast-firewall-master.svg)](https://ci.opensuse.org/view/Yast/job/yast-firewall-master/)


Since the adoption of `firewalld` this repository contains just some useful
clients and libraries for installation and autoinstallation.

YaST currently does not have a module to configure the firewall.

If you are looking for a new option, we recommend to use firewall-config to
configure your firewall via a user interface or firewall-cmd for the command line.

An **API** to configure `Firewalld` is available in this repository:

https://github.com/yast/yast-yast2/tree/master/library/network/src/lib/y2firewall

## How to add / open services in YaST modules.

For modules that just need to open a custom or predefined port in firewalld
the
[CWMFirewallInterfaces](https://github.com/yast/yast-yast2/tree/master/library/network/src/modules/CWMFirewallInterfaces.rb)
module has been adapted to work properly with the new **API.**

For more documentation refer to this [link](doc/firewalld_services.md)

## Links ##

  * See more at http://en.opensuse.org/openSUSE:YaST_development
