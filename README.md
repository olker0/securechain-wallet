Securechain Wallet 0.10.0
====================

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2013-2014 SecureCoin Developers
Copyright (c) 2015-2018 Securechain Developers

Distributed under the MIT/X11 software license, see the accompanying
file COPYING or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), UPnP software written by Thomas Bernard and
sphlib 3.0 by Thomas Pornin.


Intro
---------------------
Securechain wallet is the official Securecoin wallet. Securecoin is a
free open source peer-to-peer electronic cash system that is
completely decentralized, without the need for a central server or trusted
parties.  Users hold the crypto keys to their own money and transact directly
with each other, with the help of a P2P network to check for double-spending. It is secured by six different algorithms and its CPU only mining is another security strength. 


Build
---------------------
This is an internal test version, which has only been tested on Ubuntu 14.04 without guarantee of its functionality.
The build details can be found under [Unix Build Notes](doc/build-unix.md).


Development tips and tricks
---------------------------
**compiling for debugging**

Run configure with the --enable-debug option, then make. Or run configure with
CXXFLAGS="-g -ggdb -O0" or whatever debug flags you need.


Developers
---------------------
The main developer of SecureCoin core wallet is baritus.

The main developer of Securechain Wallet is Haimin Zhang ([contact@securechain.com](mailto:contact@securechain.com)) and Baritus.


Other Pages
---------------------
- [Unix Build Notes](doc/build-unix.md)
- [OSX Build Notes](build-osx.md)
- [Windows Build Notes](build-msw.md)
- [Coding Guidelines](coding.md)
- [Release Process](doc/release-process.md)
- [Release Notes](doc/release-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Unit Tests](unit-tests.md)
- [Translation Process](translation_process.md)
