The goal of this project was to familiarize myself with auditing pc's and automating that process into a siem through splunk.
There will be two sets of instruction for win and linux.

How to for Linux
--
Note: I will be using Lynis, you can pull it from my forked version or from the one below


 ## Installation

There are multiple options available to install Lynis.

### Software Package

For systems running Linux, BSD, and macOS, there is typically a package available. This is the preferred method of obtaining Lynis, as it is quick to install and easy to update. The Lynis project itself also provides [packages](https://packages.cisofy.com/) in RPM or DEB format suitable for systems systems running:
`CentOS`, `Debian`, `Fedora`, `OEL`, `openSUSE`, `RHEL`, `Ubuntu`, and others.

Some distributions may also have Lynis in their software repository: [![Repology](https://repology.org/badge/tiny-repos/lynis.svg)](https://repology.org/project/lynis/versions)

Note: Some distributions don't provide an up-to-date version. In that case it is better to use the CISOfy software repository, download the tarball from the website, or download the latest GitHub release.

### Git

The very latest developments can be obtained via git.

1. Clone or download the project files (**no compilation nor installation** is required) ;

        git clone https://github.com/CISOfy/lynis

2. Execute:

        cd lynis && ./lynis audit system

If you want to run the software as `root` (or sudo), we suggest changing the ownership of the files. Use `chown -R 0:0` to recursively alter the owner and group and set it to user ID `0` (`root`). Otherwise Lynis will warn you about the file permissions. After all, you are executing files owned by a non-privileged user.

- Info above pulled from README.md https://github.com/CISOfy/lynis



[Under Construction]
