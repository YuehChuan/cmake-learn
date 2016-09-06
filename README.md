# cmake-learn
 CMake turtorial sample code

#exp2 write your own hello lib

compile: 
$cd ~/code/exp2/src
$cmake .
$make

usage:
$./hello

#exp3 use libPNG in CMake, and buile subdirectory 
pre-install
$sudo apt-get install libpng-dev libzip

compile: 
$cd ~/code/exp3/build
$cmake ..
$make

usage:
under path ~/code/exp3
$./pngsample france.png italy.png

#exp4 qt window example
$cd ~/code/exp4
$cmake .
$make

usage:
./qthelloworld

ref:
https://drakeguan.org/blog/2008/03/ba-wan-CMake-de-di-yi-bu/
