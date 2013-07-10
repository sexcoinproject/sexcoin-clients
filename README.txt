Copyright (c) 2009-2012 Bitcoin Developers
Copyright (c) 2011-2012 Litecoin Developers
Copyright (c) 2013 Sexcoin Developers
Distributed under the MIT/X11 software license, see the accompanying
file COPYING or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).


Sexcoin QT Clients v0.6.3.1-beta
================================

Windows
-------
The Sexcoin-QT Windows binaries in this release are all inclusive and should
NOT require any dependencies. The binaries were build on a 32-bit architecture
but testing shows it runs fine on 64-bit systems as well. 

Linux 32-bit and 64-bit
-----------------------
Both binaries (sexcoin-qt and sexcoind) were built on Ubuntu 13.04. The 
dependency requirements are listed below. These binaries should run fine on 
older releases of Ubuntu, however they were only tested on 13.04 with the
specific library versions of ...

Boost v1.53
Berkeley DB v4.8
OpenSSL v1.0.1c

*If you are having problems getting libdb4.8 to install due to it not being
included in the 13.04 release, please see the following site which is used
for the Bitcoin-QT builds. The needed libs are provided for most current
Ubuntu releases as well as 13.04.

https://launchpad.net/~bitcoin/+archive/bitcoin