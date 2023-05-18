# Artery Framework

Below are the commands required for installing Artery V2X Framework in Ubuntu 22.04.2 LTS


| Command | Description |
| ------------- | ------------- |
| `sudo apt install git`  | Installing Git  |
| `git clone --recurse-submodule https://github.com/riebl/artery.git`  | Cloning Artery Repository  |
| `g++ --version` | Check G++ Version|
| `clang --version` | Check Clang Version |
| `sudo apt install cmake` | Install CMake Version |
| `tar xvfz [file name]` | Extract the OMNeT++ downloaded File|
| `sudo apt-get install build-essential clang lld gdb bison flex perl \python3 python3-pip qtbase5-dev qtchooser qt5-qmake qtbase5-dev-tools \libqt5opengl5-dev libxml2-dev zlib1g-dev doxygen graphviz libwebkit2gtk-4.0-37` | Installing Pre-Requisites for OMNeT++ for Ubuntu 20 or above |
| `python3 -m pip install --user --upgrade numpy pandas matplotlib scipy seaborn posix_ipc` | PreRequisites for OMNeT++|
| `sudo apt install libgeographic-dev` | |
| `sudo apt libcrypto++-dev` | |
| `sudo apt-get install sumo sumo-tools sumo-doc` | Installing SUMO |
| `sudo apt install default-jre` | Install Java |


---
Video: Creating a Custom Simulation Setup in Artery V2X Framework

| Command | Description |
| ------------- | ------------- |
|`add_subdirectory(junction)` | To add project in the CMakeLists.txt file in scenarios folder |
|`projParameter="+proj=utm +zone=22 +ellps=WGS84 +datum=WGS84 +units=m +no_defs”` | Latitude/Longitude Error |
| `cmake ..`| To Run CMake |
| `cmake --build .` | To build a Project |
| `cmake --build build --target run_junction` | Run the Project Junction|
