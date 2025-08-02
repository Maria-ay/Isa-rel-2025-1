# apt
apt 2.6.1 (amd64)
Usage: apt [options] command

apt is a commandline package manager and provides commands for
searching and managing as well as querying information about packages.
It provides the same functionality as the specialized APT tools,
like apt-get and apt-cache, but enables options more suitable for
interactive use by default.

Most used commands:
  list - list packages based on package names
  search - search in package descriptions
  show - show package details
  install - install packages
  reinstall - reinstall packages
  remove - remove packages
  autoremove - automatically remove all unused packages
  update - update list of available packages
  upgrade - upgrade the system by installing/upgrading packages
  full-upgrade - upgrade the system by removing/installing/upgrading packages
  edit-sources - edit the source information file
  satisfy - satisfy dependency strings

See apt(8) for more information about the available commands.
Configuration options and syntax is detailed in apt.conf(5).
Information about how to configure sources can be found in sources.list(5).
Package and version choices can be expressed via apt_preferences(5).
Security details are available in apt-secure(8).
                                   Este APT tem Poderes de Super Vaca.
apt

[0m[0mPackage manager for Debian-based distributions.
Intended as a user-friendly alternative to apt-get for interactive use.
For equivalent commands in other package managers, see https://wiki.archlinux.org/title/Pacman/Rosetta.
More information: https://manned.org/apt.8.

 - [0m[32;23;22;24;25mUpdate the list of available packages and versions (recommended before running other apt commands):
   [33;23;22;24;25msudo apt update[0m
[0m
 - [0m[32;23;22;24;25mSearch packages by name or description:
   [33;23;22;24;25mapt search [0mpackage
[0m
 - [0m[32;23;22;24;25mSearch packages by name only (supports wildcards like *):
   [33;23;22;24;25mapt list [0mpackage
[0m
 - [0m[32;23;22;24;25mShow detailed information about a package:
   [33;23;22;24;25mapt show [0mpackage
[0m
 - [0m[32;23;22;24;25mInstall a package, or update it to the latest version:
   [33;23;22;24;25msudo apt install [0mpackage
[0m
 - [0m[32;23;22;24;25mRemove a package (use purge instead to also remove configuration files):
   [33;23;22;24;25msudo apt remove [0mpackage
[0m
 - [0m[32;23;22;24;25mUpgrade all installed packages to their latest versions:
   [33;23;22;24;25msudo apt upgrade[0m
[0m
 - [0m[32;23;22;24;25mList all installed packages:
   [33;23;22;24;25mapt list [0m[-i|--installed]
[0m[0m