# Computer Vision - C++

## Cmake

### Download
```
cd ~/Downloads
wget https://github.com/Kitware/CMake/releases/download/v3.20.0/cmake-3.20.0.tar.gz
```

### Extract the contents
```
tar -zxvf cmake-3.20.0.tar.gz
```

### Run the command below to compile and install CMake in your Ubuntu system
```
cd cmake-3.20.0
sudo apt-get --no-install-recommends install mingw-w64 git qt4-qmake qt4-default nsis
sudo apt-get install build-essential
sudo apt-get install libssl-dev
sudo ./bootstrap
sudo make 
sudo make install
```

### Clean up
```
cd ../
sudo rm -rf cmake-3.20.0
rm -rf cmake-3.20.0.tar.gz
```

# To confirm that CMake installed successfully
```
cmake --version
```

## OpenCV 4
