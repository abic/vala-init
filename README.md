Vala Project Init
=================

This is just a template repo with a few scripts to allow me to set up new
vala projects more quickly. The ultimate goal is to implement more build and
test features as WAF Tools.

Usage
-----

    mkdir my-awesome-project
    cd my-awesome-project
    vala-project init
    vala-project add-lib my-library
    vala-project add-bin my-program

Directory Structure
-------------------

    .
    ├── COPYING
    ├── lib.pc.in
    ├── README.md
    ├── src
    │   ├── bin
    │   │   └── my-program
    │   │       └── build.cfg
    │   └── lib
    │       └── my-library
    │           └── build.cfg
    ├── tests
    │   ├── helpers
    │   │   └── testcase.vala
    │   └── lib
    │       └── my-library
    │           └── build.cfg
    ├── version.cfg
    ├── waf
    └── wscript
