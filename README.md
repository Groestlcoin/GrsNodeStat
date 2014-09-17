BtcNodeStat
===========

display statistiques for a bitcoind node

ex : http://5.135.182.69


bower
-----
```
bower install
```


cron
----
```
*/1 * * * * bitcoind getinfo > /var/www/getinfo.json
*/1 * * * * bitcoind getnettotals > /var/www/getnettotals.json
*/1 * * * * bitcoind getpeerinfo > /var/www/getpeerinfo.json
```
