# zap-client [Apex Cheat] [Linux]
**Updated to Game Version v3.0.62.29 (Season 20) (27.03.24)**

Maintained By **Magneto**

All credits to original owners

Instructions & Menu Previews are down below

# Current Changelog:
    v3.0.62.29
    Updated Offsets


# Installation
**1.Install dependencies**

    sudo apt-get install -y libudev-dev
    sudo apt install cmake xorg-dev libglu1-mesa-dev libxrandr-dev libxinerama-dev libxcursor-dev libxi-dev
    sudo apt install -y libudev-dev libglu1-mesa-dev libxkbcommon-dev libwayland-dev git cmake g++ gcc libinput-dev libsoil-dev
    sudo apt-get install build-essential
    sudo apt-get install libx11-dev
    sudo apt-get install libxtst-dev

**2.Build glfw**

    git clone https://github.com/glfw/glfw.git
    cd glfw
    mkdir build
    cd build
    cmake ..
    make
    sudo make install

**3. Clone repo**

    git clone
    cd zap-client

**4. Build and Run**

    mkdir build
    cd build
    cmake ..
    make
    sudo ./zapclient
    
**5. Press Insert to toggle the Menu (You can only interact with the Menu and the game when the menu is active).**

