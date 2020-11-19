# EIC Spack Software Stack Configuration

This repository contains configuration files in $SPACK_ROOT/etc/spack for the EIC Spack repository on cvmfs. It is checked out at `/cvmfs/eic.opensciencegrid.org/packages/spack/current/etc/spack`.

The configuration performs a few user-oriented functions:
- it sets the repository on `/cvmfs/eic.opensciencegrid.org` as an upstream resource,
- it sets the install_tree path for downstream users to a directory in `$HOME`,
- it defines the compilers and external packages for some common operating systems.

Please report any bugs at to the main [EIC Spack](http://github.com/eic/eic-spack) repository.
