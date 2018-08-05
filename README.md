
Ijgncoin ElectrumX - Reimplementation of electrum-server
-------------

This is SPV server for Electrum wallet

For a future network with bigger blocks.

- Licence: IJGN
- Language: Python (>= 3.6)

Documentation
=============
- Clone project
- cd ijgncoin-electrumx
- virtualenv -p python3 env
- source env/bin/activate
- python setup.py install
- edit `server.conf` file in the same directory
- run: `./electrumx_server start`


Sample `server.conf` file
```
COIN=Ijgncoin
DB_DIRECTORY=<directory>
DAEMON_URL=http://user:password@127.0.0.1:10332/
NET=mainnet
TCP_PORT=50001
PEER_DISCOVERY=on
FORCE_PROXY=on
PEER_ANNOUNCE=on
REPORT_TCP_PORT_TOR=0
```
