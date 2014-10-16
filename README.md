# BIOMD0000000290: Alexander2010_Tcell_Regulation_Sys2

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000290.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000290.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000290 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is system 2, the model with Michelis Menten type antigen uptake by pAPCs,
described in the article:  
**Self-tolerance and Autoimmunity in a Regulatory T Cell Model.**   
Alexander HK, Wahl LM. _Bull Math Biol._ 2010 Mar 2. PMID:
[20195912](http://www.ncbi.nlm.nih.gov/pubmed/20195912) , doi:
[10.1007/s11538-010-9519-2](http://dx.doi.org/10.1007/s11538-010-9519-2) ;  
**Abstract:**   
The class of immunosuppressive lymphocytes known as regulatory T cells (Tregs)
has been identified as a key component in preventing autoimmune diseases.
Although Tregs have been incorporated previously in mathematical models of
autoimmunity, we take a novel approach which emphasizes the importance of
professional antigen presenting cells (pAPCs). We examine three possible
mechanisms of Treg action (each in isolation) through ordinary differential
equation (ODE) models. The immune response against a particular autoantigen is
suppressed both by Tregs specific for that antigen and by Tregs of arbitrary
specificities, through their action on either maturing or already mature pAPCs
or on autoreactive effector T cells. In this deterministic approach, we find
that qualitative long-term behaviour is predicted by the basic reproductive
ratio R (0) for each system. When R (0) < 1, only the trivial equilibrium
exists and is stable; when R (0)>1, this equilibrium loses its stability and a
stable non-trivial equilibrium appears. We interpret the absence of self-
damaging populations at the trivial equilibrium to imply a state of self-
tolerance, and their presence at the non-trivial equilibrium to imply a state
of chronic autoimmunity. Irrespective of mechanism, our model predicts that
Tregs specific for the autoantigen in question play no role in the system's
qualitative long-term behaviour, but have quantitative effects that could
potentially reduce an autoimmune response to sub-clinical levels. Our results
also suggest an important role for Tregs of arbitrary specificities in
modulating the qualitative outcome. A stochastic treatment of the same model
demonstrates that the probability of developing a chronic autoimmune response
increases with the initial exposure to self antigen or autoreactive effector T
cells. The three different mechanisms we consider, while leading to a number
of similar predictions, also exhibit key differences in both transient
dynamics (ODE approach) and the probability of chronic autoimmunity
(stochastic approach).

Originally created by libAntimony v1.4 (using libSBML 3.4.1)


