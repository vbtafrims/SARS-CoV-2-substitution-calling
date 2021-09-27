# SARS-CoV-2-substitution-calling

Last updated: 27 Sep 2021

`SC2_substitution_main.sh` is a bash script for calling nucleotide and amino acid substitution of SARS-Cov-2 genome. The script requires SARS-CoV-2 genomes multiple-fasta and a reference SARS-CoV-2 genome. This script will generate a report of nucleotide and amino acid substitution at each postion (but does not include ambiguous bases and indels), a summary of variations, and a summary of silent/non-silent mutations. 


# Dependencies

- bedtools v2.30.0 (https://bedtools.readthedocs.io/en/latest/)
- datamash v1.1.0 (https://anaconda.org/bioconda/datamash)
- emboss v6.6.0.0 (https://anaconda.org/bioconda/emboss)
- gotranseq v.0.2.1 (https://github.com/feliixx/gotranseq)
- mafft v7.487 (https://mafft.cbrc.jp/alignment/software/)
- samtools v.1.12 (http://www.htslib.org/)
- seqtk v1.3-r106 (https://github.com/lh3/seqtk)
