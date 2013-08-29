cogneurotools
=============

#$Date$
#$Author: John Herrington$ 
#$Id$#

This repository contains a variety of scripts that automate the use of 
various software packages in the domain of cognitive neuroscience (primarily
neuroimaging).  It is predicated on the idea that there are a lot of extremely
useful ways in which command-line MRI analysis tools could be used,
but generally aren't, as the implementations are not obvious enough.
But just because they aren't obvious doesn't mean they are also not simple...
this is why this repository exists.

Some notes about the repository:

1) Almost all of the contents are either bash or python scripts.  For the python
    scripts, the minimal number of modules possible have generally been used,
    emphasizing the portability of the scripts across python installations and
    versions over fancier solutions that various modules might provide.

2) Most of the neuroimaging scripts wrap around either the FSL of AFNI
    software suites.  These need to be a) downloaded, b) accessible in one's
    default path, and c) have all needed environment variables initialized.
    The standard installs of FSL and AFNI take care of all this.
