cpushareholder-stub
===================

Summary
-------
Stubbed implementation of the webOS CPU shares scripts

Description
-----------
This component provides NOP implementations of the `setcpushares-*`
scripts, which are invoked by a number of other Open webOS components.

How to Build on Linux
=====================

Dependencies
------------

Below are the tools (and their minimum versions) required to build
_cpushareholder-stub_:

- cmake (version required by webosose/cmake-modules-webos)
- webosose/cmake-modules-webos 1.0.0 RC3

Building
--------
Once you have downloaded the source, enter the following to build it (after
changing into the directory under which it was downloaded):

    $ mkdir BUILD
    $ cd BUILD
    $ cmake ..
    $ make
    $ sudo make install

The directory under which the files are installed defaults to `/usr/local/webos`.
You can install them elsewhere by supplying a value for `WEBOS_INSTALL_ROOT`
when invoking `cmake`. For example:

    $ cmake -D WEBOS_INSTALL_ROOT:PATH=$HOME/projects/webosose ..
    $ make
    $ make install

will install the files in subdirectories of `$HOME/projects/webosose`.

If not specified, `WEBOS_INSTALL_ROOT` defaults to `/usr/local/webos`.

To see a list of the make targets that `cmake` has generated, enter:

    $ make help

Uninstalling
------------
From the directory where you originally ran `make install`, enter:

    $ [sudo] make uninstall

You will need to use `sudo` if you did not specify `WEBOS_INSTALL_ROOT`.

Copyright and License Information
=================================
Unless otherwise specified, all content, including all source code files and
documentation files in this repository are:

Copyright (c) 2012-2018 LG Electronics, Inc.

Unless otherwise specified or set forth in the NOTICE file, all content,
including all source code files and documentation files in this repository are:
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this content except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

SPDX-License-Identifier: Apache-2.0
