# Service provision example

This repository deploys an [Nginx](http://wiki.nginx.org/Main) web server in a virtual machine and exposes it to the host port `8080`. Provisioning is provided by [SaltStack](http://saltstack.com/).

## Usage

You need to have [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/) installed. Once that's done simply navigate to the root directory of this project at a command line and enter `vagrant up`. Once Vagrant's finished doing its thing you can visit `localhost:8080` to see the web server in operation.
