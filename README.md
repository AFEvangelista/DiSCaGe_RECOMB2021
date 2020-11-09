# DiSCaGe (Discovering Significant Cancer Genes)

All sources to reproduce paper results are available.

The following libraries and versions were used:
 - Python 3.7.7
 - pandas 1.0.5
 - numpy 1.18.5
 - networkx 2.4
 - matplotlib 3.2.2
 

## Usage

DiSCaGe has 3 options for use:

**Type 1:**
- Mutation data on MAF file format
- Gene interaction network in edge lists

**Type 2:**
- Binary mutation matrix
- Weighted mutation matrix
- Gene interaction network in edge lists

**Type 3:**
- Mutation score for each gene
- Gene interaction network in edge lists



A input file must be filled with data and the weights for each Variant_Classification. A running example is set on the file *EXAMPLE_SNV_InDel_input_parameters.in*, which is run using the follow command
    
    python DiSCaGe.py EXAMPLE_SNV_InDel_input_parameters.in


  
## Contact

Please, feel free to contact me: 
 - cutigi@ifsp.edu.br
 - cutigi@usp.br
