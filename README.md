kostenlose Virtualisierungssoftware
===================================

* VMWare Player: http://www.vmware.com/products/player/overview.html
* VirtualBox: https://www.virtualbox.org/

VMWare Player kann im Gegensatz zu VirtualBox keine Snapshots machen

Ubuntu Installation
===================

MongoDB Installation
--------------------

```bash
sudo cp Dateien/etc/apt/sources.list.d/10gen.list /etc/apt/sources.list.d/
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv 7F0CEB10
sudo apt-get update
sudo apt-get install mongodb-10gen
```

http://docs.mongodb.org/manual/tutorial/install-mongodb-on-ubuntu/
