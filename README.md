There are two script 'branches' in this repository. One has a hardcoded blacklist to remove AppX applications for all users; the other pulls from the cloud. I have modified two scripts based off this original one. The files prepended with original_ are unmodified from the original:

A new script "Aggro" borrows app removal from multiple sources in a very ugly manner. It adds some registry keys to a key under "Deprovisioned" for whatever reason. I've not merged that change yet.

https://github.com/MSEndpointMgr/Windows/

The modifications here poing to an updated blacklist.txt hosted on this repository.
