# apt-cyg / sage

The apt-cyg project and bash script was renamed to Sage on January 23, 2016.  

**When the project was renamed the MIT license was removed.  This is not legal.**  

This repo is an attempt to restore a correct working copy of apt-cyg, and repair the improperly removed license.

Commit b6076c2 is apt-cyg prior to the rename and license removal/
Commit 6f0fd05 is the most recent commit after the name change.

# README for apt-cyg and Sage

---

apt-cyg
=======

apt-cyg is a Cygwin package manager. It includes a command-line installer for
Cygwin which cooperates with Cygwin Setup and uses the same repository.

[github.com/transcode-open/apt-cyg][1]

[![bountysource][3]][2]

[1]:https://github.com/transcode-open/apt-cyg
[2]:https://www.bountysource.com/teams/svnpenn
[3]:https://api.bountysource.com/badge/team?team_id=114003&style=raised

Operations
----------

~~~
install
  Install package(s).

remove
  Remove package(s) from the system.

update
  Download a fresh copy of the master package list (setup.ini) from the
  server defined in setup.rc.

download
  Retrieve package(s) from the server, but do not install/upgrade anything.

show
  Display information on given package(s).

depends
  Produce a dependency tree for a package.

rdepends
  Produce a tree of packages that depend on the named package.

list
  Search each locally-installed package for names that match regexp. If no
  package names are provided in the command line, all installed packages will
  be queried.

listall
  This will search each package in the master package list (setup.ini) for
  names that match regexp.

category
  Display all packages that are members of a named category.

listfiles
  List all files owned by a given package. Multiple packages can be specified
  on the command line.

search
  Search for downloaded packages that own the specified file(s). The path can
  be relative or absolute, and one or more files can be specified.

searchall
  Search cygwin.com to retrieve file information about packages. The provided
  target is considered to be a filename and searchall will return the
  package(s) which contain this file.
~~~

Quick start
-----------

apt-cyg is a simple script. To install:

    lynx -source rawgit.com/transcode-open/apt-cyg/master/apt-cyg > apt-cyg
    install apt-cyg /bin

Example use of apt-cyg:

    apt-cyg install nano

This repo is a restoration of the latest version of apt-cyg (currently January 22nd 2016).

---
---

Sage
====

Sage is a Cygwin package manager. It includes a command-line installer for
Cygwin which cooperates with Cygwin Setup and uses the same repository.

[![bountysource][2]][1]

[1]:https://www.bountysource.com/teams/svnpenn
[2]:https://api.bountysource.com/badge/team?team_id=114003&style=raised

Operations
----------

~~~
install
  Install package(s).

remove
  Remove package(s) from the system.

update
  Download a fresh copy of the master package list (setup.ini) from the
  server defined in setup.rc.

download
  Retrieve package(s) from the server, but do not install/upgrade anything.

show
  Display information on given package(s).

depends
  Produce a dependency tree for a package.

rdepends
  Produce a tree of packages that depend on the named package.

list
  Search each locally-installed package for names that match regexp. If no
  package names are provided in the command line, all installed packages will
  be queried.

listall
  This will search each package in the master package list (setup.ini) for
  names that match regexp.

category
  Display all packages that are members of a named category.

listfiles
  List all files owned by a given package. Multiple packages can be specified
  on the command line.

search
  Search for downloaded packages that own the specified file(s). The path can
  be relative or absolute, and one or more files can be specified.

searchall
  Search cygwin.com to retrieve file information about packages. The provided
  target is considered to be a filename and searchall will return the
  package(s) which contain this file.
~~~

Quick start
-----------

Sage is a simple script. To install:

    lynx -source rawgit.com/svnpenn/sage/master/sage > sage
    install sage /bin

Example use of Sage:

    sage install nano
