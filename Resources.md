# Useful resources 
## Models
Where to find metabolic models (or genome wide metabolic models)?
- [BIGG database](http://bigg.ucsd.edu/): a great resource for well curated models. The disadvantage is that they do not have many environmental bacteria. 
- [Virtual Metabolic Human](https://www.vmh.life/#microbes/search): has a collection of metabolic models of bacterial species associated with the gut.  

For environmental resources isolates it is best to reconstruct them from available genomes. This can be easily done within *The Department of Energy Systems Biology Knowledgebase* [KBase](https://narrative.kbase.us/#catalog/apps/fba_tools/build_metabolic_model/release). **KBase** uses [RAST](https://www.anl.gov/mcs/rast-rapid-annotation-using-subsystem-technology#:~:text=The%20RAST%20(Rapid%20Annotation%20using,a%2048%20hour%20turnaround%20time) for genome annotation, the [SEED](https://modelseed.org/) framework for building models, and their own gap fill metabolic model tool. 

## Tutorials

### FBA 
- [COBRA](https://opencobra.github.io/cobratoolbox/latest/index.html) website is full of tutorials 
- The same is true of [COBRApy](https://cobrapy.readthedocs.io/en/latest/getting_started.html)

### COMETS
- [COMETS tutorial page](https://segrelab.github.io/comets-manual/)
- [Github repository](https://github.com/segrelab/COMETS_Protocols/tree/master/COMETS_protocols) of different COMETS protocols

## Manuals 
- [COMETSpy](https://cometspy.readthedocs.io/en/latest/index.html)

## Articles 
- **[Orth, Thiele, and Palsson (2011)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3108565/)** Great introduction to FBA
- **[Harcombe, et al. (2014)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4097880/)** First COMETS paper introducing the overall logic of the program and its use in simple spatially structured interactions. 




This repository has the materials for a workshop introducing FBA and COMETS (Computation Of Microbial Ecosystems in Time and Space). To learn more about COMETS I recommend checking their [website](https://www.runcomets.org/home) and the papers linked there and in the resources document in this repository.

This repository and the materials within are building upon code written by others and I want to give credit where credit is due: 
- *COMETS* is a collaboration between multiple labs and it is mantained by the [Segre Lab](https://github.com/segrelab/comets) at Boston University
- The *CAFBAfy* file (this version) is written mostly by Jean C.C. Vila (https://github.com/vilacelestin) with some minor modifications by me 
- The *FBA tutorial* is a modification (by me) of a tutorial by Jean C.C. Vila

I will keep updating useful resources, but suggestions are welcome. 

