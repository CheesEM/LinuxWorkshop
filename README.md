VMWare Workstation
==================

Snapshots 
---------
* ermöglichen das Speichern des aktuellen Standes einer virtuellen Maschine
* man kann zwischen Snapshots beliebig hin- und herspringen

Netzwerkeinstellungen
---------------------
* NAT: VM tritt im Netzwerk "im Namen des Hostes" auf - Host sorgt dafür das die Netzwerkpakete richtig weiter geleitet werden
* Bridged: VM ist "ganz normal im Netzwerk"
* Host-Only: VM und Host kommunizieren direkt, und nicht über das echte Netzwerk

kostenlose Alternativen
-----------------------
* VMWare Player: http://www.vmware.com/products/player/overview.html
* VirtualBox: https://www.virtualbox.org/

VMWare Player kann im Gegensatz zu VirtualBox keine Snapshots machen

Ubuntu Installation
===================

Nützliche Links
---------------
* http://www.ubuntu.com/
* http://wiki.ubuntuusers.de/Startseite
* http://www.linuxforen.de/forums/index.php
* https://launchpad.net

Alternative Ubuntu-Derivate mit anderen Desktop Environments
------------------------------------------------------------
* http://www.kubuntu.org/ (KDE)
* http://xubuntu.org/ (XFCE)
* http://lubuntu.net/ (LXDE)
* https://wiki.ubuntu.com/UbuntuGNOME/ReleaseNotes/12.10 (Gnome3)

weitere unter https://wiki.ubuntu.com/DerivativeTeam/Derivatives

Interessante Links
------------------
* http://distrowatch.com/
* http://www.pro-linux.de/
* http://www.linux-magazin.de/

Sublime Text 2 Installation
---------------------------

```bash
sudo add-apt-repository ppa:webupd8team/sublime-text-2
sudo apt-get install sublime-text
```

https://launchpad.net/~webupd8team/+archive/sublime-text-2

MongoDB Installation
--------------------

```bash
sudo cp Dateien/etc/apt/sources.list.d/10gen.list /etc/apt/sources.list.d/
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv 7F0CEB10
sudo apt-get update
sudo apt-get install mongodb-10gen
```

http://docs.mongodb.org/manual/tutorial/install-mongodb-on-ubuntu/
