# vagrant-escenic

A Vagrant box for installing Escenic CMS

## Software versions:

- Escenic Engine 5.7.50.169448
- Assembly tool 2.0.7
- Tomcat 7.0.63
- MySQL Connector 5.1.36
- Java jdk-8u45-linux-x64


## Usage

- vagrant up
- ssh into box with escenic user: ssh -p 2222 escenic@localhost 
- run 'ece deploy'
- run 'ece start'
- go to localhost:8080/escenic-admin to verify installation.


## Problems?

- Verify that all urls in install-escenic-5.7.sh are up and working