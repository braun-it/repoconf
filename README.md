# repoconf
## Repository Configuration

This tool and its configuration files are used to create RPM packages and push them into an existing repository.
Prerequesites for this tool are whiptail, dialog, createrepo and apache. The packages names can vary, depending on the distribution.

All you need, is a tar file of the scripts and functions you want in the RPM file and a filled in spec file.
For further information, please refer to the manual of rpmbuild

Under */etc* there is the configuration file where you can adjust the variables, which you need for e.g. different folder layout or loglevel for debugging.

Under */bin* you can find the executable binary script which starts all configurations and functions.

Under */opt/repoconf* we have the functions for e.g. building packages or reloading the repository.
