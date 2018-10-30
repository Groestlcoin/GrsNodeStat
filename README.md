GrsNodeStat
===========

display statistiques for a groestlcoind node

bower
-----
```
bower install
```


cron
----
```
*/1 * * * * groestlcoind getblockchaininfo > /var/www/getblockchaininfo.json
*/1 * * * * groestlcoind getnetworkinfo > /var/www/getnetworkinfo.json
*/1 * * * * groestlcoind getnettotals > /var/www/getnettotals.json
*/1 * * * * groestlcoind getpeerinfo > /var/www/getpeerinfo.json
```
