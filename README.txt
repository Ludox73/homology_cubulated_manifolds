============================================
Dodecahedral L-spaces and hyperbolic 4-manifolds, Section 3
============================================

This is part of the code and data accompanying the paper

* Ludovico Battista, Leonardo Ferrari and Diego Santoro; Dodecahedral L-spaces
and hyperbolic 4-manifolds, 2022.

It consists of several files written by Ludovico Battista and Leonardo Ferrari.

Running the programs
====================

The easiest way to use the code is to open the worksheets inside Jupyter.
To work, the code needs Sage with Regina installed. We used Sage version 9.1.

The worksheets
====================

The worksheet "Compute_Dod_maps_from_IsoSig.ipynb" contains the routines
necessary to obtain the gluings of the facets of the dodecahedra given a the
barycentric subdivision of the tessellation of a dodecahedral manifold.

The worksheet "Computing homology of the 3-manifold.ipynb" computes the
homology of the manifold obtained by gluing dodecahedra along facets. It is
used to check the output of "Compute_Dod_maps_from_IsoSig.ipynb".

The worksheet "Get_combinatorics_facet_Wplus.ipynb" computes the gluing of
the facets of the 120-cells that produce the manifold W'_+ (see Section 3 of
the paper).

The worksheet "Computing homology of 4-manifold.ipynb" computes the homology of
the explicit examples we found (see Tables 3-4-5-6 of the paper).


Getting help
============

This part addresses a very specific construction described in the paper, and
we were unsure what, if any, parts of this code would be of general interest.
For this reason the documentation is not very detailed. In any case, if you have
any questions about how these programs work or need help getting them to work
for you, you are encouraged to contact us.

License
=======

As its authors, we (Ludovico Battista and Leonardo Ferrari) hereby release this
code and data into the public domain, as per:

  https://creativecommons.org/publicdomain/zero/1.0/legalcode
