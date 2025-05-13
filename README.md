This is part of a project that I'm currently building that can classify how likely specific mutations in DNA are to cause diseases (variant effect prediction) by using the state-of-the-art Evo2 large language model, and use it to predict the pathogenicity of single nucleotide variants (SNVs). Currently working on a web application where users can select a genome assembly, browse its chromosomes or search for specific genes like BRCA1, and view the gene's reference genome sequence. The user can input a mutation in the gene and predict its pathogenicity with AI, but the user can also pick from a list of existing known variations, and compare the Evo2 prediction (pathogenic/benign) against existing ClinVar classifications.  


Check out the paper behind the model.

- [Paper](https://www.biorxiv.org/content/10.1101/2025.02.18.638918v1)
- [GitHub Repository](https://github.com/ArcInstitute/evo2) (EVO2 LLM)
