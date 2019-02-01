
# Architecture Test Suite Software requirements

## Prerequisite
Before starting the test suite build, ensure that the following requirements are met: <br />

- Host Operating System     : Ubuntu 16.04
- Scripting tools           : Perl 5.12.3
- Compiler toolchain        : GNU Arm Embedded Toolchain 6.3.1, Arm Compiler v6.7

*Note*: To compile Test Suite code, at least one of the above supported compiler toolchains
        have to be available in the build environment.

### Setup a shell to enable compiler toolchain after installation

To import GNU Arm in your bash shell console:
~~~
export PATH=<GNU_ARM_PATH>/bin:$PATH
~~~

To import Arm Compiler in your bash shell console:
~~~
export PATH=<ARM_COMPILER_PATH>/bin:$PATH
~~~

## Download source

To download the master branch of the repository, type the following command: <br />
~~~
git clone https://github.com/ARM-software/psa-arch-tests.git
~~~

## License
Arm PSA test suite is distributed under Apache v2.0 License.

--------------

*Copyright (c) 2018-2019, Arm Limited and Contributors. All rights reserved.*