================
Tigger Changelog
================

1.3.5
=====

 * Provide MS list to tigger-convert --app-to-int operation (#69)
 * Tigger incompatible with pyfits>=3.4 (#71)
 * It's given the correct name (install_requires) so that it will actually have an
   effect on the package manager.
 * PyQt4 is removed from install_requires, since it is not a PyPA-installable package.
   Instead, a check is added to fail setup if it is not already installed.
 * Added missing scipy and pyfits dependencies.



1.3.3
=====

 * renamed package to astro-tigger to resolve name conflict on pypi


