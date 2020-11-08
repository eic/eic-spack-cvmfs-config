# EIC Spack Software Stack Configuration

This repository contains the configuration files in $SPACK_ROOT/etc/spack for the /cvmfs/eic.opensciencegrid.org Spack repository. It is checked out at `/cvmfs/eic.opensciencegrid.org/packages/spack/rollout/etc/spack`.

The configuration performs a few user-oriented functions:
- it sets the repository on `/cvmfs/eic.opensciencegrid.org` as an upstream resource,
- it sets the install_tree path for downstream users to a directory in `$HOME`,
- it defines the compilers and external packages for some common operating systems.
