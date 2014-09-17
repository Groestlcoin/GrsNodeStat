BtcNodeStat
===========

display statistiques for a bitcoind node

ex : http://5.135.182.69


bower
-----
bower install


cron
----
*/1 * * * * /opt/bitcoin-0.9.2.1-linux/bin/64/bitcoind getinfo > /var/www/getinfo.json > /dev/null
*/1 * * * * /opt/bitcoin-0.9.2.1-linux/bin/64/bitcoind getnettotals > /var/www/getnettotals.json > /dev/null
*/1 * * * * /opt/bitcoin-0.9.2.1-linux/bin/64/bitcoind getpeerinfo > /var/www/getpeerinfo.json > /dev/null

