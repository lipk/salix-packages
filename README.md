salix-packages
==============

Some SLKBUILDs for Salix OS.

Building packages
==============

First, make sure that the software listed in the .deps file of the package is
installed on your computer. After that you can compile tha package with

cd {package directory}
slkbuild
su -c "./build-{packagename}.sh"

And finally install with

su -c installpkg {package file}.txz
