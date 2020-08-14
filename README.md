# Mining

EthMiner : !wget https://github.com/82a/mining/raw/master/ethminer && chmod +x * && ./ethminer -G -P stratum1+tcp://wallet@pool:port

ccminer/8.21-KlausT : !sudo apt install cuda 9.1 && sudo apt install libcurl4-nss-dev && sudo apt install libcurl3-nss && dpkg -L libcurl3-nss | grep libcurl-nss.so.4 && wget https://github.com/82a/mining/releases/download/8.21-KlausT/ccminer && chmod +x * && ./ccminer -a algo -o pool:port -u wallet.worker

LolMiner : !wget https://github.com/82a/mining/raw/master/lolMiner &&  ./lolMiner -a algo --pool pool:port --user wallet.worker
BEAM-I
BEAM-II
BEAM-III
C29D
C29Z
C30CTX
C31
C32
EQUI144_5
EQUI192_7
EQUI210_9
ZEL
