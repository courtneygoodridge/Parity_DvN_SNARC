# Parity experiment: Digits vs Numerosity

**Disclaimer**: *This is a working repository and so information and code may change.*

## Overview

Many studies highlight that people represent numbers on mental numbers. Evidence of this occurs in the SNARC (spatial–numerical association of response codes) effect, whereby people are faster to respond with left key pressses for small numbers and faster right key presses for large numbers. In a previous piece of work [(Prpic et al, 2023)](https://link.springer.com/article/10.3758/s13423-023-02246-w), we investigated whether the SNARC effect interacted with symbolic (digits) and non-symbolic (dots) numerals. Analysis code and data for that experiment can be found [here](https://github.com/courtneygoodridge/DvN_manuscript_analysis). 

The code, analysis, and data in the current respository is a conceptual replication of this previous study. The stimuli, the design and the procedure are the same; the only main difference is the task which consists of a parity judgment (i.e., is the number odd or even?) instead of a magnitude classification (i.e., is the number small or large?). 

## Code and analysis

The `Dice_SNARC2.zip` file contains the [PsychoPy](https://www.psychopy.org/) script that runs the experiment. PsychoPy is a free software tool that allows researchers to run Psychology experiments using open source software. The `.xlsx` files are used by the PsychoPy scripts to render the stimuli for the experiment.

The `Parity_Analysis_Script.Rmd` analysis script can be found in the analysis folder. To run the analysis, glone the `Parity_DvN_SNARC` repository into your working directory (you can find this by running the here::here() function in the R command line). For more information on using the `here::here()`, see the [documentation](https://here.r-lib.org/). Once the repository is in your working directory, run each chunk of code in turn. Session information is provided below in the case of package dependencies. A draft write up of the results can be found in the Manuscript folder, alongside some plots in the Plots folder. 

## Session info

`sessioninfo()`

<img width="295" alt="image" src="https://github.com/courtneygoodridge/Parity_DvN_SNARC/assets/44811378/53d76452-512e-445b-a85b-2b4a4462ed3c">






