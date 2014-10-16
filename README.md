# BIOMD0000000415: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000415.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000415.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000415 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** Reduction of off-flavor generation in soybean homogenates: a mathematical model. **   
Mellor N , Bligh F , Chandler I , Hodgman C _ J. Food Sci._2010 Sep; 75(7):
R131-8; PMID: [2153556](http://www.ncbi.nlm.nih.gov/pubmed/2153556),  
**Abstract:**   
The generation of off-flavors in soybean homogenates such as n-hexanal via the
lipoxygenase (LOX) pathway can be a problem in the processed food industry.
Previous studies have examined the effect of using soybean varieties missing
one or more of the 3 LOX isozymes on n-hexanal generation. A dynamic
mathematical model of the soybean LOX pathway using ordinary differential
equations was constructed using parameters estimated from existing data with
the aim of predicting how n-hexanal generation could be reduced. Time-course
simulations of LOX-null beans were run and compared with experimental results.
Model L(2), L(3), and L(12) beans were within the range relative to the wild
type found experimentally, with L(13) and L(23) beans close to the
experimental range. Model L(1) beans produced much more n-hexanal relative to
the wild type than those in experiments. Sensitivity analysis indicates that
reducing the estimated K(m) parameter for LOX isozyme 3 (L-3) would improve
the fit between model predictions and experimental results found in the
literature. The model also predicts that increasing L-3 or reducing L-2 levels
within beans may reduce n-hexanal generation. PRACTICAL APPLICATION: This work
describes the use of mathematics to attempt to quantify the enzyme-catalyzed
conversions of compounds in soybean homogenates into undesirable flavors,
primarily from the compound n-hexanal. The effect of different soybean
genotypes and enzyme kinetic constants was also studied, leading to
recommendations on which combinations might minimize off-flavor levels and
what further work might be carried out to substantiate these conclusions.


