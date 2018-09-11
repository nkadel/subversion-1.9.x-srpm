SRPM tools for Subversion 1.9.x

This github repo includes tools for building subversion-1.9.x
RPM's. It is based on the SCLo build of subversion 1.9.

There's a seriously updated "get-deps.sh", and new dependencies on
libserf instead of neton. libserf has been added to EPEL.

There is a relatively new component, "mod_dondothat". This is packaged
with mod_dav_svn, and provides limitations on server-burdensome
operations such as checking out entire repository trees.

To build locally, use "make build".

To use mock to build for EPEL 7 and others, use "make"
