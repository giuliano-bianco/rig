# rig
A GAP package for racks, quandles, Nichols algebras

Rig is a GAP package for computations related to racks, quandles, knots, virtual knots, Nichols algebras.

Download
--------
Latest stable version here (tar.gz), or here (zip), version 1.

News
----
Now Rig contains all indecomposable quandles of size <48! Check out the sequence A181771.

Features
--------
Racks and quandles
* groups associated to finite racks and quandles 
* complete list of non-isomorphic indecomposable quandles of order < 48 
* rack and quandle homology
* quandle colorings of knots
* quandle 2-cocycle invariants of knots
* Nelson's polynomials invariants

Nichols algebras
* derivations
* dimensions and relations for gbnp package

Databases
* indecomposable quandles of size <48
* planar diagrams for knots of <13 crossings (from Livingstone's website)
* planar diagrams for virtual knots up to <6 crossings (from Green's website)

Authors
-------
* L. Vendramin
* M. Graña (retired)

Cite as
-------
If you have used Rig in the preparation of a paper please cite it as:

L. Vendramin. Rig, a GAP package for racks, quandles and Nichols algebras. Available at http://github.com/vendramin/rig/

Contributions
-------------
You are welcome to contribute with code, patches, ideas, testing, wiki, comments, documentation. See the wiki for the list of contributors. Special thanks go to: W. E. Clark, D. Holt, A. Hulpke, A. Lochmann, G. Royle, M. Saito, D. Stanovsky.

Usage
-----
See the wiki to learn how to install the package.

To load the package:

gap> LoadPackage("rig");
If you want to see some examples follow this link.

Examples
--------
Here you will find many examples (constructions of racks and quandles, quandle 2-cocycles abelian extensions, quandle colorings and 2-cocyle invariants of knots, calculations related to Nichols algebras...

References
----------
Here you can find a comprehensive list of references relevant to quandles and related topics (work in progress). Help me to improve this list!

Links
-----
* GAP - Groups, Algorithms, Programming - a System for Computational Discrete Algebra   [http://www.gap-system.org/]
* GBNP, GAP Package for Gröbner Bases for Non-commutative Polynomials [http://mathdox.org/products/gbnp/]
* Sage: Open Source Mathematics Software [http://www.sagemath.org/]
* Small Connected Quandles and Their Knot Colorings [http://shell.cas.usf.edu/~saito/QuandleColor/]
* KnotInfo: Table of knot invariants, by C. Livingston and J. Cha [http://www.indiana.edu/~knotinfo/]
* A table of virtual knots, by Jeremy Green [http://www.math.toronto.edu/drorbn/Students/GreenJ/index.html]
