# Bonyx

For OS Ubuntu 16.04.7 LTS (Xenial Xerus):

### Name: Bonyx (BNX)

[Bonyx project](https://github.com/bonyx-project/)

### Repository:

[Bonyx](https://github.com/bonyx-project/bonyx/) - [Bonyx wallet](https://github.com/bonyx-project/bonyx-wallet/) - [Bonyx logo](https://github.com/bonyx-project/bonyx-logo/)
##
### Total money supply:
500000000000000.00 BNX

### Minable (1%):
5000000000000.00 BNX

### Premine (99%):
495000000000000.00 BNX
##
### Bonyx cryptocurrency symbol:
Symbol: BNX
### Bonyx cryptocurrency unicode character:
Unicode character (U+0D6B): ൫
##
### Block time:
120s

### Block reward is the same almost forever (for 1 million years):
18.18 BNX + TRANSACTION FEES

### Transaction fee: 
0.01 BNX per 1 transaction
##
### Address prefix:
Addresses start with "bx"

### Default ports for P2P and RPC networking:
P2P PORT: 15050, RPC PORT: 15051
##
## Building Bonyx:
Install OS Ubuntu 16.04.7 LTS (Xenial Xerus):

[Install Ubuntu - Ubuntu 16.04.7 LTS (Xenial Xerus)](https://releases.ubuntu.com/xenial/)

[Download Ubuntu 64-bit PC desktop image](https://releases.ubuntu.com/xenial/ubuntu-16.04.7-desktop-amd64.iso) - ubuntu-16.04.7-desktop-amd64.iso

SHA 256 file hash:

8ba7e2687fb8a2152504475e92e489aace543059fd4ba7ffe10111c42394853b *ubuntu-16.04.7-desktop-amd64.iso
##
Install Rufus:

[Install Rufus for create bootable USB flash disk](https://rufus.ie)

[Install Rufus 64-bit PC](https://github.com/pbatard/rufus/releases/download/v4.6/rufus-4.6.exe) - rufus-4.6.exe
##
### After installing OS Ubuntu 16.04.7 LTS (Xenial Xerus):
Open Terminal - CTRL + ALT + T
##
### Installing dependencies:
1. Installing cmake 2.8.12.2
```
sudo apt-get update
sudo apt-get install cmake
```
2. Installing make
```
sudo apt-get update
sudo apt-get install make
```
3. Installing git
```
sudo apt-get update
sudo apt-get install git
```
##
1. Install
```
sudo apt install build-essential libqt4-dev qt5-qmake cmake qttools5-dev libqt5webkit5-dev qttools5-dev-tools qt5-default python-sphinx texlive-latex-base inotify-tools openssl libssl-dev libdb++-dev libminiupnpc-dev git sqlite3 libsqlite3-dev g++ libpng-dev gedit python gcc make libbz2-dev libdb-dev libssl-dev libreadline-dev autoconf libtool libleveldb-dev libblkid-dev e2fslibs-dev libboost-all-dev libaudit-dev nano qtbase5-dev qt4-dev-tools libqtcore4 libqtgui4 automake -y
```
2. Install
```
sudo apt-get install build-essential
```
3. Install
```
sudo apt-get install g++
```
4. Install
```
sudo apt-get install clang
```
5. Install
```
sudo apt-get install boost
```
6. Install
```
sudo apt-get install libboost-all-dev
```
Restart PC.
##
### Install & Build Bonyx:
1. Clone bonyx sources
```
git clone https://github.com/bonyx-project/bonyx.git
```
2. Go to directory /bonyx/
```
cd bonyx
```
3. Build
```
make
make -j
make
make -j
```
(ignore errors)
##
### Run:
1. Go to directory /bonyx/build/release/src/
```
cd bonyx/build/release/src
```
2. Run
```
./bonyxd
```
3. Simplewallet (Open new Terminal - CTRL + ALT + T). Go to directory /bonyx/build/release/src/ (Step 1)
```
./simplewallet
```
##
##
### Useful commands:
Delete existing blockchain
```
rm -rf ~/.bonyx
```
