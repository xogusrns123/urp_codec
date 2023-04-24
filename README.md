# urp_codec
libvpx 사용
libvpx install 방법:
1. build
```
git clone https://github.com/webmproject/libvpx.git
./configure
make
```
만약 ./configure에서 error: prerequisites가 존재한다. 내 경우에는 yasm이 없어서 문제였음
```
sudo apt-get install yasm
```
2. install
```
sudo make install
```
