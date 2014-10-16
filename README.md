# MODEL1006230012: Stewart2009_ActionPotential_PurkinjeFibreCells

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230012.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230012.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230012 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Mathematical models of the electrical action potential of Purkinje fibre cells.**   
Philip Stewart, Oleg V. Aslanidi, Denis Noble, Penelope J. Noble, Mark R.
Boyett and Henggui Zhang. _Phil. Trans. R. Soc. A_ 13 June 2009 vol. 367 no.
1896 2225-2255
[doi:10.1098/rsta.2008.0283](http://dx.doi.org/10.1098/rsta.2008.0283) ,  
**Abstract:**   
Early development of ionic models for cardiac myocytes, from the pioneering
modification of the Hodgkin–Huxley giant squid axon model by Noble to the
iconic DiFrancesco–Noble model integrating voltage-gated ionic currents, ion
pumps and exchangers, Ca2+ sequestration and Ca2+-induced Ca2+ release,
provided a general description for a mammalian Purkinje fibre (PF) and the
framework for modern cardiac models. In the past two decades, development has
focused on tissue-specific models with an emphasis on the sino-atrial (SA)
node, atria and ventricles, while the PFs have largely been neglected.
However, achieving the ultimate goal of creating a virtual human heart will
require detailed models of all distinctive regions of the cardiac conduction
system, including the PFs, which play an important role in conducting cardiac
excitation and ensuring the synchronized timing and sequencing of ventricular
contraction. In this paper, we present details of our newly developed model
for the human PF cell including validation against experimental data. Ionic
mechanisms underlying the heterogeneity between the PF and ventricular action
potentials in humans and other species are analysed. The newly developed PF
cell model adds a new member to the family of human cardiac cell models
developed previously for the SA node, atrial and ventricular cells, which can
be incorporated into an anatomical model of the human heart with details of
its electrophysiological heterogeneity and anatomical complexity.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **CellMLdetails**
](http://models.cellml.org/exposure/b6f7d1d53e85f24d4afb9f31d3bc622a)  
The original CellML model was created by:  
**Penny Noble**   
penny.noble@dpag.ox.ac.uk  
The University of Oxford  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not. .  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


