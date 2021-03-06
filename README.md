unstructInterp
==============

R routines for unstructured interpolation. A few methods are implemented which
work relatively efficiently on semi-large datasets (e.g. millions of points).

The code relies heavily on other packages (FNN + geometry), and its
purpose is mainly to provide a convenient interface to some efficient interpolation
methods (and save us hacking to use them elsewhere!), rather than on developing
novel interpolation methods.

Note that many other R packages have routines for unstructured interpolation,
and only a few methods are supported here. 

Installation
------------
Make sure you have the 'devtools', 'FNN', and 'geometry' package installed in R:
>    install.packages(c('devtools','FNN','geometry'))

Then you can install direct from github

>    install_github('GeoscienceAustralia/unstructInterp')

To get started, look at the examples (which also function as unit tests) and help:

> library(unstructInterp)
>
> example(nearest_neighbour_interpolation)
>
> ?nearest_neighbour_interpolation
>
> example(triangular_interpolation)
>
> ?triangular_interpolation

Maintenance and Contributions
-----------------------------

This code is sporadically developed based on the needs of the developers and
colleagues. The open source release is mainly to assist with our own management
of the code, as well as to allow others to use it. Bugfixes/suggestions are
nonetheless welcome. 

If you'd like to contribute any routines or fix bugs, consider forking the
code, inserting your changes and sending the maintainer a pull request.
Otherwise bug reports / suggestions can be sent to the maintainer Gareth
Davies, gareth.davies.ga.code@gmail.com 

Note that the documentation in /man is auto-generated from within-code comments using the roxygen2 package.

License
-------
This code is licensed under a BAD 3-clause license. See the [license deed](LICENSE) for details

Contaces
--------
**Gareth Davies**  
*Lead Devloper*  
<gareth.davies@ga.gov.au>  

