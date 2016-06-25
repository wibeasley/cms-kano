Botball Software
=======================================

### Install pre-reqs

Install [packages through `apt-get`](https://github.com/kipr/kiss#requirements).

```shell
sudo apt-get install qtbase5-dev
sudo apt-get install cmake
sudo apt-get install libqscintilla2-dev   
sudo apt-get install g++
sudo apt-get install codeblocks
sudo apt-get install qtquick1-5-dev
sudo apt-get install qtscript5-dev
sudo apt-get install qttools5-dev
sudo apt-get install qttools5-dev-tools

# sudo apt-get install libkovanserial
# sudo apt-get install pcompiler
# sudo apt-get install libkar
```
References:
* http://community.botball.org/forum/technical/programming/installing-kiss-ide-ubuntu?page=1#comment-7910

```shell
git clone git://github.com/kipr/libkar.git
git clone git://github.com/kipr/pcompiler.git
git clone git://github.com/kipr/libkovanserial.git
git clone git://github.com/kipr/kiss.git

cd libkar
mkdir build
cd build/
cmake ..
sudo make install

cd ../../pcompiler/
mkdir build
cd build/
cmake ..
sudo make install

cd ../../libkovanserial/
mkdir build
cd build/
cmake ..
sudo make install

cd ../../kiss/
mkdir build
cd build/
cmake ..
sudo make install # Failed here.

./deploy/KISS
```
