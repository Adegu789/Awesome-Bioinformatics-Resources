Awesome-Bioinformatics
======================

A curated list of awesome Bioinformatics software and libraries. Mostly command line based, and free or open-source.

__Data Processing__

* [Command Line Utilities](#command-line-utilities)

__Next Generation Sequencing__

* [Sequence Processing](#sequence-processing)
* [Sequence Alignment](#sequence-alignment)
* [Variant Calling](#variant-calling)
* [Variant Prediction](#variant-prediction)


## Data Processing

### Command Line Utilities

* [datamash](http://www.gnu.org/software/datamash/) - Data transformations and statistics. 
* [Bioinformatics One Liners](https://github.com/stephenturner/oneliners) - Git repo of useful single line commands.

## Next Generation Sequencing

### Sequence Processing 

Sequence Processing includes tasks such as demultiplexing raw read data, and trimming low quality bases.

* [Fastqp](https://github.com/mdshw5/fastqp) - Fastq and Sam quality control using python.
* [FastQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/) - A quality control tool for high throughput sequence data.
	* Series of quality control checks for raw sequence data.
* [Fastx Tookit](http://hannonlab.cshl.edu/fastx_toolkit/) - FASTQ/A short-reads pre-processing tools
	* Demultiplexing (fastx\_barcode\_splitter.pl)
	* Trimming, Clipping
	* Quality Filtering
	* Masking
* [Seqtk](https://github.com/lh3/seqtk) - Toolkit for processing sequences in FASTA/Q formats.
	* FASTQ --> FASTA conversion
	* Nucleotide Composition (Number of A,T,C,G)
	* Add point mutations to FASTA

### Sequence Alignment

__De Novo Alignment__

__DNA Resequencing__

* [BWA](https://github.com/lh3/bwa) - Burrow-Wheeler Aligner for pairwise alignment between DNA sequences. 

### Variant Calling

* [samtools/bcftools/htslib](https://github.com/samtools/samtools) - A suite of tools for manipulating next-generation sequencing data.
	* SNVs
	* Indels - Called using gapped alignments.
* [freebayes](https://github.com/ekg/freebayes) - Bayesian haplotype-based polymorphism discovery and genotyping.

### Variant Filtering / Quality Control

### Variant Prediction

