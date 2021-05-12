#runnning-many-mongod-with-supervisord
##install mongod and supervisor
```bash
/bin/bash mongo-setup.sh
```
##config mongod: datastorge, log, ...
```bash
vim /etc/mongo/mongod.conf
```
##config supervisord:
```bash
vim /etc/supervisord.conf
```
##start supervisord
```bash
service supervisor start
```
