# Workshop at the INCF Neuroinformatics Assembly 2022

## Tools and formats for large scale network modelling


This workshop will be held during the [Neuroinformatics Assembly 2022](https://neuroinformatics.incf.org/2022) online conference.



### Description

A number of groups around the world are developing complex, experimentally constrained network models of neuronal function.
Creating the software infrastructure to develop, simulate and share these types of models takes a significant amount of time
for any of the groups involved and there can be a lot of overlap, duplication in work and repeated effort.

The purpose of this workshop  is to highlight some of the initiatives currently underway to build biologically detailed
neuronal network models as well as those projects building the infrastructure to make it easier to develop, disseminate and
compare the models.

This workshop is organised as part of the [INCF Working Group on Standardised Representations of Network Structures](https://github.com/NeuralEnsemble/Networks_SIG).

### Program

**Date:** Tuesday Sept 13 2022

**Time:** 19:00-20:30 CET  


| Time (CET)  | Details |
| ------------- | ------------- |
| 19:00  | **Modeling, simulating and visualizing biophysically realistic networks using the SONATA data formats with BMTK and VND**<br/>***Kael Dai, Barry Isralewitz***, *Mariano Spivak, Xiao-Ping Liu, John E. Stone, Emad Tajkhorshid, and Anton Arkhipov*<br/><br/> <details><summary>Abstract</summary><p>With the increasing availability of experimental datasets and high-performance computing it’s important as ever for network neuroscience to utilize computational modeling and simulation techniques. This has led to an increase in tools for modeling large brain networks. But as different tools often use different programming languages and even different levels-of- resolutions, that has created challenges for scientists’ ability to share, reproduce and extend each other’s work.<br/> To address these challenges the SONATA file formats were developed: a set of open-source standards for representing large-scale network models, conditions to run simulations, and simulation results. It was designed to represent large-scale heterogeneous network models and simulations in a memory and computationally efficient manner and to work across multiple levels-of-resolutions. The SONATA format is not meant to replace existing standards, and when possible incorporates already existing formats and can be extended to work with other tools and standards. The goal of SONATA is to facilitate reproducibility and interoperability between otherwise disparate tools and software. <br/>To demonstrate the utility of the SONATA formats we showcase two existing tools, the Brain Modeling Toolkit (BMTK) and Visual Neuronal Dynamics (VND). BMTK is an open-source API developed at the Allen Institute for building and simulating large-scale heterogeneous network models. BMTK can work across different resolutions, automates parallelization for high-performance computing, and provides advanced features with minimal programming. VND is a network visualization tool developed at the University of Illinois. It utilizes novel techniques in rendering and data querying to visualize and analyze network models and simulations. In this talk we demonstrate how, through the SONATA file formats, one can build and simulate network models using BMTK, then use VND to visualize these models.<br/>Research reported in this publication was supported by the National Institute Of Neurological Disorders And Stroke of the National Institutes of Health under Award Number U24NS124001. The content is solely the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health</p></details> |
| 19:20  | **Model Description Format: integrating model development across computational neuroscience, cognitive science and machine learning**<br/>***David Turner, Princeton Neuroscience Institute***<br/><br/> <details><summary>Abstract</summary><p>To follow</p></details> |
| 19:40  | **On concepts, correctness, and performance of network simulations**<br/>***Johanna Senk***<br/><br/> <details><summary>Abstract</summary><p>The development of large-scale neuronal network models is an iterative process and best described by a loop linking the conceptual description with its algorithmic implementation. Models are informed by experimental data and insights from theory; their simulated dynamics needs to be validated against experimentally observed activity. The inherent interdisciplinarity and intricacy of this endeavor make it prone to pitfalls that complicate the comprehensibility and reproducibility of each step. Addressing shortcomings in model descriptions, we review how connectivity is specified in published models and propose unified connectivity concepts and guidelines including a graphical notation for network diagrams. Furthermore, we focus on the challenge to compare simulations of a cortical microcircuit model with respect to correctness and performance across different simulation technologies; literature shows a race for the fastest and most energy efficient simulation. We also showcase a conceptual workflow for performance benchmarking of the simulator NEST together with the benchmarking framework beNNch as a reference implementation. Finally, we introduce NNMT, a toolbox for mean-field based analysis methods of neuronal network models. The presented approaches aim at raising awareness to common difficulties and fostering a sustainable and collaborative modeling culture.</p></details> |
| 20:00  | **Large-scale biophysically-detailed thalamocortical models**<br/>***Salvador Dura-Bernal***<br/><br/> <details><summary>Abstract</summary><p>Biophysically-detailed models provide a quantitative theoretical framework to integrate and interpret a wide range of experimental data. They also constitute a powerful tool to evaluate hypotheses and make predictions about the cellular and network mechanisms underlying common experimental measurements, including MUA, LFP and EEG signals. We developed large-scale biophysically-detailed models of mouse motor cortical circuits, rat somatosensory thalamocortical circuits and macaque auditory thalamocortical circuits. Each model includes in the order of 10k-15k neurons and 30M synapses, with neuron densities, distribution, morphology and biophysics, as well as connectivity at the long-range, local and dendritic scales, constrained by published experimental data. To develop and simulate the models we used the NEURON simulation engine and the NetPyNE multiscale modeling tool. These models can be used to identify the cellular and circuit biophysical mechanisms underlying neural function, disease and behavior.</p></details> |
| 20:20  | Panel discussion  |




### Practicalities

Details on how to join the online workshop will be available [here](https://neuroinformatics.incf.org/2022).
