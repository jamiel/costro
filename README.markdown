Costro
======

Costro is a simple continuous integration testing tool designed to periodically check 
the stability of PECL packages in the Gentoo tree. It has the capability of building 
against multiple version of PHP and running tests to ensure each extension in the tree 
is functional post build.

Note: This tool should be run in a chrooted environment or on a server designed for
testing as it repeatedly adds and removes all pecl packages it can.
