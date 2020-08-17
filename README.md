# Mining
!nvidia-smi

function ClickConnect(){
    console.log("Working"); 
    document.querySelector("colab-connect-button").click() 
}
setInterval(ClickConnect,60000)

https://colab.research.google.com/#create=true

EthMiner : !wget https://github.com/82a/mining/raw/master/ethminer && chmod +x * && ./ethminer -G -P stratum1+tcp://wallet@pool:port

ccminer/8.21-KlausT : !sudo apt install cuda 9.1 && sudo apt install libcurl4-nss-dev && sudo apt install libcurl3-nss && dpkg -L libcurl3-nss | grep libcurl-nss.so.4 && wget https://github.com/82a/mining/releases/download/8.21-KlausT/ccminer && chmod +x * && ./ccminer -a algo -o pool:port -u wallet.worker

LolMiner : !wget https://github.com/82a/mining/raw/master/lolMiner && chmod +x * && ./lolMiner -a algo --pool pool:port --user wallet.worker

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

Trex Miner : !wget https://github.com/82a/mining/raw/master/t-rex && chmod +x * && ./t-rex -a algo -o pool:port -u wallet.worker -p x

alterhash
astralhash
balloon
bcd
bitcore
c11
dedal
geek
hmq1725
honeycomb
jeonghash
kawpow
lyra2z
mtp
mtp-tcr
padihash
pawelhash
phi
polytimos
progpow
sha256q
sha256t
skunk
sonoa
tensority
timetravel
tribus
x11r
x16r
x16rt
x16rv2
x16s
x17
x21s
x22i
x25x

MiniZ Miner : !wget https://github.com/82a/mining/releases/download/v1.6v5/miniZ && chmod +x * && ./miniZ --par=algo --url=ssl://wallet.WORKER_NAME@pool:port --log --extra --ocX

TT-Miner : !wget https://github.com/82a/mining/raw/master/TT-Miner && chmod +x * && ./TT-Miner -A algo -P wallet.worker@pool:port
ETHASH
UBQHASH
PROGPOW
MTP
LYRA2V3
EAGLESONG
