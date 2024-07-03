# Serious Business STM32 Project

This is the template/demo repository to go along with my [blog post](https://nathandumont.com/serious-business-stm32-development) about setting up a serious business STM32 project.  It's a demo of what you can do to make a robust platform for multi-threaded applications using open source tools.

On an Ubuntu system you should be able to build it if you have the following packages:

* gcc-arm-none-eabi
* cmake

To build please clone this repo, then from inside the clone folder run:

    git submodule update --init
    mkdir build
    cd build
    cmake ..
    cmake --build .

You can then program the resulting bin/hex file using OpenOCD or a GUI tool like the STM32CubeProgrammer.
