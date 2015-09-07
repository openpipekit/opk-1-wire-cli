A command line interface for interacting with the 1-wire sensor from Maxim.

Based on https://github.com/timofurrer/w1thermsensor

# Requirements
Python

# Usage
Command line example:

```
$ ./install
installing...
done.
```
Reboot
```
$ ./detect
Sensor 0000053055be has temperature 24.62
Sensor 0000052fc128 has temperature 24.56
$ ./pull --path 28-0000053055be
42
```
