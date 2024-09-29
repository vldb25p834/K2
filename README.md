# K2
This repository contains implementations for K2 core services and subsystems.

### Install instructions
 * Install chogori-seastar-rd (see instructions in Docker directory)
 * run `./install_deps.sh` to install other dependency libraries
 * build and install the cmake subprojects under src/logging and src/skvhttpclient
 * generate cmake and build `mkdir build && cd build && cmake .. && make -j`
