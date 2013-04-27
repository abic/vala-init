Vala Project Init
=================

This is just a template repo with a few scripts to allow me to set up new
vala projects more quickly. The ultimate goal is to implement more build and
test features as WAF Tools.

Usage
-----

Directory Structure
-------------------

    .
    ├── build
    ├── ci_build.sh
    ├── ci_install.sh
    ├── COPYING
    ├── docs
    ├── examples
    │   └── example-1.vala
    ├── README.md
    ├── src
    │   ├── bin
    │   │   └── my-program
    │   │       ├── build.cfg
    │   │       └── main.vala
    │   └── lib
    │       └── my-library
    │           ├── build.cfg
    │           ├── lib.vala
    │           └── my-library.pc.in
    ├── tests
    │   ├── assets
    │   │   └── test_file.txt
    │   ├── bin
    │   ├── helpers
    │   │   └── testcase.vala
    │   ├── lib
    │   │       ├── build.cfg
    │   │       ├── helpers.vala
    │   │       └── main.vala
    ├── vapi
    │   └── external.vapi
    ├── version.cfg
    ├── waf
    └── wscript

