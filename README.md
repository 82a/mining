CpuMiner : !wget https://github.com/82a/mining/blob/master/cpuminer && chmod +x * && ./cpuminer -a algo -o pool:port -u wallet.worker

EthMiner : !wget https://github.com/82a/mining/raw/master/ethminer && chmod +x * && ./ethminer -G -P stratum1+tcp://wallet@pool:port

Lolminer : !wget https://github.com/82a/mining/raw/master/lolMiner && chmod +x * && ./lolMiner --algo algo --pool pool:port --user wallet --pass x

ccminer/8.21-KlausT : !sudo apt update && sudo apt install cuda 9.1 && sudo apt install libcurl4-nss-dev && sudo apt install libcurl3-nss && dpkg -L libcurl3-nss | grep libcurl-nss.so.4 && wget https://github.com/82a/mining/releases/download/8.21-KlausT/ccminer && chmod +x * && ./ccminer -a algo -o pool:port -u wallet.worker

Trex Miner : !wget https://github.com/82a/mining/raw/master/t-rex && chmod +x * && ./t-rex -a algo -o pool:port -u wallet.worker -p x

MiniZ Miner : !wget https://github.com/82a/mining/releases/download/v1.6v5/miniZ && chmod +x * && ./miniZ --par=algo --url=ssl://wallet.WORKER_NAME@pool:port --log --extra --ocX

TT-Miner : !wget https://github.com/82a/mining/releases/download/tt-miner/TT-Miner.tar.xz && tar xf TT-Miner.tar.xz && chmod +x * && ./TT-Miner -A algo -P wallet.worker@pool:port
