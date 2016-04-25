There are several dependencies that need to be met in order to build and
install ActiveMQ-CPP on a Unix type system, the short list is shown below,
read the sections that follow for more detailed information.  On Windows
you will not need the Auto Tools since the library is built using Microsft's
Visual Studio product.

Tool        Recommended Version
-------------------------------
autoconf    >= 2.61
automake    >= 1.10
libtool     >= 1.5.24
APR         >= 1.3*
CPPUnit     >= 1.10.2* ( 1.12.1 is recommended )
OpenSSL     >= 0.9.8m* ( 1.0.0 or higher is recommended, this is an optional dependency)

* Requires that the Development package also be installed.
