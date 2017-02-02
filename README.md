# README #

### Ubuntu dependencies ###
```
sudo apt-get install gawk wget git-core diffstat unzip texinfo gcc-multilib build-essential chrpath socat cpio python python3 pip3
```

### Compiling the sama5d3xek yocto image ###

```
yocto$ source poky/oe-init-build-env build-atmel
yocto/build-atmel$ bitbake core-image-base
```

### Flashing ###
For now, use the SAM-BA GUI [Linux](http://www.atmel.com/Images/Atmel-42728-Using-SAM-BA-for-Linux-on-SMART-ARM-based-Microcontrollers_ApplicationNotes_AT15004.pdf)

ToDo: Make a tcl script for automatic flashing.
