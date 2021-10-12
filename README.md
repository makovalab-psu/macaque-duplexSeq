# macaque-duplexSeq

### Data

- **`2020-09_Rh_mut_freqs.xlsx`**: mutation frequency data to be used as input in the code `Rh_mut-freq.Rmd`, `Supplementary Note 1.Rmd` and `Supplementary Note 2.Rmd`
- **`Rh_mutations.xlsx`**: mutation data to be used as input in the code `Supplementary Note 2.Rmd`

### Code

- **`Rh_mut-freq.Rmd`**: code for fitting generalized mixed-effects linear models predicting the probability of having a mutation in a sequenced nucleotide as a function of age
- **`Supplementary Note 1.Rmd`**: code for Supplementary Note 1, analysis of mutations shared by oocytes of the same animal (the corresponding html with code output is in the file `Supplementary Note 1.html`)
- **`Supplementary Note 2.Rmd`**: code for Supplementary Note 2, variant hotspot analysis (the corresponding html with code output is in the file `Supplementary Note 2.html`)

### Output of Supplementary Note 2

- **`shared_mutation_multiple_Rh_liver.xlsx`**, **`shared_mutation_multiple_Rh_muscle.xlsx`** and **`shared_mutation_multiple_Rh_oocytes.xlsx`**: output of Supplementary Note 2, containing variants found in a tissue type in two or more macaques and their hotspot probability, i.e. the probability of the variant to be present by random chance exactly in those individual samples in which we observe it (considering the mtDNA sequencing depth of the individual samples)
