# verusminer
```
apt-get update
apt-get upgrade
```
**Paste perintah dari Andronix**
```
./start-ubuntu.sh
```
 **(Jika Eror brati kamu salah waktu install ubuntu)**

```
apt-get update
apt-get upgrade
apt install software-properties-common
add-apt-repository ppa:jonathonf/gcc
apt install git build-essential cmake libuv1-dev libssl-dev libmicrohttpd-dev gcc-7 g++-7 libhwloc-dev
apt-get install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential
git clone --single-branch -b ARM https://github.com/monkins1010/ccminer.git
cd ccminer
chmod +x build.sh
chmod +x configure.sh
chmod +x autogen.sh
./build.sh

```

To Run

```
./ccminer  -a verus  -o stratum+tcp://ap.luckpool.net:3956  -u  RBPiVgMrGswnAQvpUdQpHX2muq6kQoi8Ht.ALTOMEDIA  -p x  -t CPU 2

```


**DONASI VERUS COIN**
RBPiVgMrGswnAQvpUdQpHX2muq6kQoi8Ht
