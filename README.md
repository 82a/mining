CpuMiner : !wget https://github.com/82a/mining/blob/master/cpuminer && chmod +x * && ./cpuminer -a algo -o pool:port -u wallet.worker

EthMiner : !wget https://github.com/82a/mining/raw/master/ethminer && chmod +x * && ./ethminer -G -P stratum1+tcp://wallet@pool:port

Lolminer : !wget https://github.com/82a/mining/raw/master/lolMiner && chmod +x * && ./lolMiner --algo algo --pool pool:port --user wallet --pass x
