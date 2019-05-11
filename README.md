# MiningEobot
How to mine Eobot on Android with Termux (Terminal of Linux/ Ubuntu on Android)

Download and install Termux.apk on your android, that you can get it from playstore or else !
Run Termux !
Write and run by click enter the scripts/ commands below :
- apt update
- apt upgrade
- apt install g++9 automake
- apt install git
- apt install wget
- apt install proot
- git clone https://github.com/Neo-Oli/termux-ubuntu.git
- cd termux-ubuntu
- chmod +x ubuntu.sh
- ./ubuntu.sh
- ./start-ubuntu.sh
- apt update && apt upgrade
- apt install wget
- apt install proot
- apt install git
- apt install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev
- mkdir cpuminer
- cd cpuminer
- apt install automake autoconf pkg-config libcurl14-openssl-dev libjansson-dev libssl-dev libgmp-dev make g++
- git clone https://github.com/tpruvot/cpuminer-multi
- ./build.sh

finish.


+
now you can try your pool (eobot account) some like this :
- ./cpuminer -a sha3 -o stratum+tcp://sha.eobot.com:3333 -u eobot.1930455 -p x -t 4
--  -a = algorithm
--  -o = pool
--  -u = user
--  -p = password
--  -t = thread / cpu


+
Then, next time and every time you want mining, because you had finished the installation on your android, you can do just :
- cd termux-ubuntu
- ./start-ubuntu.sh
- cd cpuminer/cpuminer-multi
- ./cpuminer -a sha3 -o stratum+tcp://sha.eobot.com:3333 -u eobot.1930455 -p x -t 4


+
+
   - exit for quit
   
.

