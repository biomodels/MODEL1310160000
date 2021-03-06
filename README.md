# MODEL1310160000: MODEL1310160000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1310160000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1310160000.git@20140916`

## Usage

Importing the model package.

`import MODEL1310160000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes

    
    
    This model is from the paper: 
    
    Anne-Kristin Stavrum, Ines Heiland, Stefan Schuster, Pål Puntervoll, and Mathias Ziegler. (2013) Model of Tryptophan Metabolism, Readily Scalable using Tissue-Specific Gene Expression Data. J. Biol. Chem. published October 15, 2013 as doi:10.1074/jbc.M113.474908
    
    Summary:
    Tryptophan is utilised in various metabolic routes including protein synthesis, serotonin and melatonin synthesis and the kynurenine pathway. Perturbations in these pathways have been associated with neurodegenerative diseases and cancer. Here, we present a comprehensive kinetic model of the complex network of human tryptophan metabolism, based upon existing kinetic data for all enzymatic conversions and transporters. By integrating tissue-specific expression data, modelling tryptophan metabolism in liver and brain returned intermediate metabolite concentrations in the physiological range. Sensitivity and metabolic control analyses identified expected key enzymes to govern fluxes in the branches of the network. Combining tissue-specific models revealed a considerable impact of the kynurenine pathway in liver on the concentrations of neuroactive derivatives in the brain. Moreover, using expression data from a cancer study predicted metabolite changes that resembled the experimental observations. We conclude that the combination of the kinetic model with expression data represents a powerful diagnostic tool to predict alterations in tryptophan metabolism. The model is readily scalable to include more tissues, thereby enabling assessment of organismal tryptophan metabolism in health and disease.


