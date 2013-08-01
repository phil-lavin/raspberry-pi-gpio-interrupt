Intro
=====

Small C programme to demonstrate how to use kernel level GPIO interrupts on a Raspberry Pi. Also includes time based jitter filtering.

Compiling
---------

* Clone the repository
* Follow the instructions at http://wiringpi.com/download-and-install/ to install the WiringPi library on your Pi
* ```gcc -lwiringPi -o gpio-interrupt gpio-interrupt.c```

Running
-------
Must be run as root

```
./gpio-interrupt
```
