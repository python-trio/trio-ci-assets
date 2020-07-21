This repository contains certain binaries that are used in Trio's continuous integration tests. They are encrypted so that we aren't publicly distributing anything that asks not to be publicly distributed.

Currently includes:
* `komodia-based-vpn-setup.zip`: contains the installer for a Komodia-based Windows VPN. (Komodia is a toolkit for making Windows applications that trap network accesses. Trio carries some special logic to work in the presence of Komodia-based applications, which we have tests for.)
