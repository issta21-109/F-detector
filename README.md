

dependencies
--------------
build-essentials
libssl-dev

needs
--------
IDA 3.4
python3.5


configuration
-------------------
file: config.makefile
change IDA_EXE and IDA_T_EXE to the path to the executables if ida64 and idat64

build
------
make


configure tests
----------------
file: config.sh
change project to the path to the cloned directory


run test
----------
cd test/Test_cases
./busybox.sh

- intermediate results are stored in tests/results
- output: executable busybox-patched





