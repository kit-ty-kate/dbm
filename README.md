# The CamlDBM library

## OVERVIEW

This OCaml library is a binding to the NDBM/GDBM Unix "databases" -- more exactly, persistent key-value stores.

See the file `dbm.mli` for documentation of the programming inteface.

This library used to be included in the standard OCaml distribution. This is the standalone distribution of this library, with the same functionalities.


## REQUIREMENTS

* OCaml
* Either the GDBM library or any NDBM-compatible library.  Make sure to install the development files as well.  For Debian or Ubuntu, install the package `libgdbm-compat-dev` if it exists, otherwise the package `libgdbm-dev`.


## INSTALLATION

* Run the "configure" script by typing
       ./configure

* Build the library:
       make all

* Test the library:
       make test

* Install the library:
       sudo make install


## USAGE

In bytecode:
     ocamlc dbm.cma <other bytecode files>

In native code:
     ocamlopt dbm.cmxa <other bytecode files>


## LICENSE

This Library is distributed under the terms of the GNU Library General Public License version 2, with a special exception allowing unconstrained static linking.  See file LICENSE for details.


     
