# ubuntu 18.04

# dependence
```
sudo apt-get install -y build-essential cmake pkg-config libboost-all-dev libssl-dev libzmq3-dev libunbound-dev libnorm-dev libpgm-dev libsodium-dev libminiupnpc-dev libunwind8-dev liblzma-dev libreadline6-dev libldns-dev libexpat1-dev libgtest-dev doxygen graphviz
```

# ibraries needed : boost >=1.58

How to compile this :
```
git clone https://github.com/.....
cd laniakeymkdir build
cd build
cmake -D STATIC=ON -D CMAKE_BUILD_TYPE=RELEASE ..
PORTABLE=1 make
```
