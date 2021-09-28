# Pyclone_input_generator
This program creates inputs for Pyclone run from SNV, copy number data for
multiple samples from a patient.

The following are four patients with multiple samples
1.sample1__pyclone_input.txt
2.sample2__pyclone_input.txt,
3.sample3__pyclone_input.txt,
4.sample4__pyclone_input.txt,

Each sample with patient has copy number, gene, mutation, chromosomal position, ref /alt allele, total reads and mutant reads. The sex is provided for adjusting X chromosome total copy number.

The a_pyclone_inputfiles_generation.ipynb reads all the input files and writes the output in
Pyclone_inputs folder.

To do:
Change  your working directory accordingly . 

The resulting input files can be used with purity information for pyclone run . 
