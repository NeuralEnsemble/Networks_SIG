## Workshop report: Developing, standardising and sharing large scale cortical network models

*A workshop at CNS 2018, Tues 17th July, Allen Institute, Seattle*

### Background

A number of groups around the world are developing complex, experimentally constrained 
models of cortical function. Creating the software infrastructure to develop, simulate 
and share these types of models takes a significant amount of time for any of the groups 
involved and there can be a lot of overlap, duplication in work and repeated effort.

The purpose of this workshop was to highlight some of the initiatives currently underway to build 
detailed cortical models as well as those projects building the infrastructure to make 
it easier to develop, disseminate and compare the models. 

This workshop was the first activity of the [INCF Special Interest Group (SIG)](https://www.incf.org/activities/standards-and-best-practices/incf-special-interest-groups) on 
[Standardised Representations of Network Structures](https://www.incf.org/activities/standards-and-best-practices/incf-special-interest-groups/incf-sig-on-standardised). 
For more details on the current activities of this initiative, see [here](https://github.com/NeuralEnsemble/Networks_SIG). 

### Presentations

#### Sacha van Albada

*Jülich Research Centre, Germany*

**Large scale model development from the [NEST](http://www.nest-simulator.org) perspective**

Sacha presented an overview of activities within the NEST community related to creating large scale models of networks constrained at multiple scales. 
She presented first the motivation for creating large scale models (with numbers of neurons closer to real networks) and the need for multiscale models, 
which can be compared to experimental data at the micro-, meso- and macroscale. The multilayer cortical network model of 
[Potjans and Diesmann (2014)](https://www.ncbi.nlm.nih.gov/pubmed/23203991) was described, which was originally developed in NEST, and has been ported to 
PyNN, Brian and Spinnaker, and is [available on OSB](http://www.opensourcebrain.org/projects/potjansdiesmann2014). 

The Potjans and Diesmann model has formed the basis of a multi area model of macaque visual cortex ([Schmidt et al., 2018](https://link.springer.com/article/10.1007/s00429-017-1554-40)). Sacha described the technical 
challenges of building a model of this complexity in NEST, the experimental data used to constrain the model, the activity of the simulated network as well as 
insights which can be gained from analysis of the connectivity of the model. The model, together with extensive documentation is available at https://github.com/INM-6/multi-area-model.

*Slides for this presentation are available [here](https://github.com/NeuralEnsemble/Networks_SIG/blob/master/docs/CNS2018/van_Albada_CNS2018_multi_area_model.pdf).*


#### Anton Arkhipov<sup>1</sup> and Eilif Muller<sup>2</sup>

*1: Allen Institute, Seattle, USA; 2: Blue Brain Project, Switzerland*

**Data-Driven Modeling of Brain Circuits and the [SONATA Data Format](https://github.com/AllenInstitute/sonata)**

Eilif and Anton presented joint work between the Allen Institute and the Blue Brain project 
to come up with a format for exchanging information on large scale simulations between the two initiatives. 
[Sonata](https://github.com/AllenInstitute/sonata)

*Slides for this presentation are available [here](https://github.com/NeuralEnsemble/Networks_SIG/blob/master/docs/CNS2018/2018-07-SONATA_Arkhipov_Muller.pdf).*

#### Salvador Dura-Bernal

*SUNY Downstate Medical Center, Brooklyn, NY, USA*

**Development of large scale data-driven network models in [NetPyNE](http://www.netpyne.org/), a high-level interface to [NEURON](https://www.neuron.yale.edu/neuron)**

Salvador presented 
desire to make it easier to create, manage and analyse large scale models in the neuron simulator

M1 network model
Already NeuroML compatible
Graphical interface


*Slides for this presentation are available [here](https://github.com/NeuralEnsemble/Networks_SIG/blob/master/docs/CNS2018/CNS18_workshop_NetPyNE.pdf).*

#### Padraig Gleeson

*University College London, UK*

**Large scale cortical models in [NeuroML](https://www.neuroml.org/) format on [Open Source Brain](http://www.opensourcebrain.org/)**

Padraig presented the latest developments with NeuroML, a standardised language 
OSB models, including from bioRxiv
NeuroMLlite


*Slides for this presentation are available [here](https://github.com/NeuralEnsemble/Networks_SIG/blob/master/docs/CNS2018/CNS2018-NeuroMLOSBCorticalModels.pdf).*

### Discussion and future plans


There was general agreement t

all open

Concrete steps going forward
nml-pynn
Sonata - NeuroML, PyNN, NetPyNE

Activities of the SIG will continue and the next online videoconference for the 



