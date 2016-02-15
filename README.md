# Relay Network code

[![Build Status](https://img.shields.io/travis/BitcoinRelayNetwork/RelayNode.svg?branch=master&style=flat-square)](https://travis-ci.org/BitcoinRelayNetwork/RelayNode)

See http://bitcoinrelaynetwork.org/ for information on the network

## Building with Vagrant

Vagrant is a machine virtualization tool for creating and managing virtual development environments. If you do not have Vagrant installed, you can download it here: https://www.vagrantup.com/downloads.html

From within the project's top-level directory, execute `vagrant up`. This will boot up a virtual machine, install necessary dependencies, and build the relay node executable. In order to rebuild, execute `vagrant provision --provision-with build`.
