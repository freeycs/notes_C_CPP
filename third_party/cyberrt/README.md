
# README

- [README](#readme)
  - [编译](#编译)
  - [编译过程分析](#编译过程分析)

## 编译

sudo apt install build-essential git cmake
sudo apt install -y libpoco-dev uuid-dev libncurses5-dev python3-dev python3-pip
python3 -m pip install protobuf==3.14.0

sudo ./scripts/install.sh
mkdir build && cd build
cmake ..
make -j${nproc}

## 编译过程分析
