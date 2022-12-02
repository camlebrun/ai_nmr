# Prediction 

In this part, we wiiologiclall try to predict NMR spectra from a protein sequence. To avoid to perform biological experiments (mutation, production, puridication ...) 

*Algorithms for prediction*
* [Shiftx2](https://github.com/camlebrun/ai_nmr/blob/5731b4beeadf1cafef2999762249d4f6623209e4/Publications/shiftx2.pdf)
  * Principle: 
    * Sub algo: 
  * Problems: 
## Steps by step algo
**DEEP LEARNING NO HARD CODE HERE**

* Collect data set form NMRDB (or lab)
* Choose alogrithm able to predict chemical shift from sequence 
  * Probalistic model 
    * Atoms
    * molecules
    * Neighbors


## Steps by step user 
<ins>Input:</ins>
* enter you protein sequence (1 letter code)
* enter your parameters (not useful for script)

<ins>Output:</ins>
* Prediction of chemical shift in <sup> 13 </sup>C, <sup> 15</sup>N, <sup> 1 </sup>H with secondary structure 
* Plot (dot or cross) with <sup> 13 </sup> - <sup> 1 </sup>H  &  <sup> 1 </sup>H - <sup> 15</sup>N (more readable) 
* *Just for UX:*
    * add chemical shift of each  amino acid next to the structure 