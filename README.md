# Dockerized Dash Masternode

Version: 0.12.1

### Usage

start with you own dash.conf by simply running:

`docker run tomasen/dashd-masternode -v /root/.dashcore:/path-to-local-storage-that-contain-dash.conf`

or just save the time of writing any dash.conf config file by running:

`docker run tomasen/dashd-masternode -v /root/.dashcore:/path-to-local-storage -e MN_PRIVATE_KEY`

There are four key envirment viaribles:

MN_PRIVATE_KEY | Required
MN_EXTERNAL_IP | Optional
MN_RPCBIND     | Optional
MN_RPCALLOWIP  | Optional

WARNING: start docker container is such way will overwrite existing dash.conf in local storage.

### Debug

* * *
Donations are welcome at [XxkCgrET2pKXbF1eYyPxSqQvWpJQ6qYncG](https://chainz.cryptoid.info/drk/search.dws?q=XxkCgrET2pKXbF1eYyPxSqQvWpJQ6qYncG). Thanks
