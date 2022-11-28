# NMR and AI project
**Documents and collaborative repo**
## Stakeholders

* Camille Lebrun @camlebrun
* G.Lippens
  
## Introduction
* This project will be a long term project in order to create robust and efficient algorithms/models.  
* We can imagine two distinct parts:
  * Prediction of NMR spectra from a protein sequence (see "predict" file)
  * Assignment of NMR spectra to a protein sequence + NMR spectra (nD) (see "assign" folder)

We can specialize the models on protein families if we have enough data and/or if the outpouts are not accurate enough


## Objectives
To create prediction and assignment models of NMR spectra from protein sequences and/or NMR spectra.
Why ? 
* To facilitate data processing 
* In-silico biology
* Human VS machine contraction
* "Uniformity" of results 

## Constraints 

The production of biological samples can be "heterogeneous", unwanted mutations, "non conforming" folding, etc. 

The purification of biological samples can denature all or part of the sample and create artifacts (cleavage, precipitation etc.)

The acquisition of NMR spectra are not performed under the same conditions (temperature, pH, implantation sequences, etc.)

All these parameters influence the chemical shifts or the quality of the obtained spectra.

It is then necessary to create robust and efficient models in order to be able to apply them on "heterogeneous" and "noisy" data. 

That is to say, to be able to create models that will not give "false" or "inconsistent" outpouts depending on the input data.

Translated with www.DeepL.com/Translator (free version)