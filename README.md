# lib_install
for install
 1) 安装依赖项
 sudo apt-get install libglew-dev
 sudo apt-get install libboost-dev libboost-thread-dev libboost-filesystem-dev
 sudo apt-get install libpython2.7-dev
 2) 安装Pangolin
 git clone https://github.com/stevenlovegrove/Pangolin.git
 cd Pangolin
 mkdir build 
 cd build 
 cmake -DCPP11_NO_BOOSR=1 .. 
 make -j
