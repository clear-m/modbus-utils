modbus-utils
============

Modbus client and server command line tools based on libmodbus.

NOTE:
Both apps are linked with libmodbus library. After repository is pulled do the following:

Linux preliminaries
===========

```sh
sudo apt install libmodbus-dev
```

compilation
===========

```sh
mkdir build
cd build
cmake ..
cmake --build .
```

running
=======

```sh
./modbus_client
```

usage
=====

Run apps with no arguments, descriptive help information will be provided.
