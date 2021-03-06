# Genomics #

## quality control ##  

1. [fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)

version 0.11.4

A quality control tool for high throughput sequence data.

`fastqc -h`

12. [trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic)

Trimmomatic: A flexible read trimming tool for Illumina NGS 

`trimmomatic`

3. [blobtools](https://blobtools.readme.io/docs)  

A modular command-line solution for visualisation, quality control and taxonomic partitioning of genome datasets  

*under construcion*  

4. [BUSCO](https://gitlab.com/ezlab/busco)  

Assessing genome assembly and annotation completeness with Benchmarking Universal Single-Copy Orthologs (BUSCO)

*under construction*  

## genome and transcriptome assembly ##

1. [kmergenie](http://kmergenie.bx.psu.edu)

version 1.7044

KmerGenie estimates the best k-mer length for genome de novo assembly. 

2. [SPAdes](http://spades.bioinf.spbau.ru/release3.10.1/manual.html#sec2.1)

version 3.10.1

SPAdes – St. Petersburg genome assembler – is an assembly toolkit containing various assembly pipelines. 

3. [trinity](https://github.com/trinityrnaseq/trinityrnaseq/wiki)

version 2.4.0

Trinity assembles transcript sequences from Illumina RNA-Seq data.

`trinity`  

4. [NOVOPlasty](https://github.com/ndierckx/NOVOPlasty)

version 2.6.2

NOVOPlasty is a de novo assembler for short circular genomes.

`novoplasty`

5. [DBG2OLC](https://github.com/yechengxi/DBG2OLC)  
 
DBG2OLC:Efficient Assembly of Large Genomes Using Long Erroneous Reads of the Third Generation Sequencing Technologies  

`DBG2OLC` `AssemblyStatistics` `SelectLongestReads` `Sparc` `SparseAssembler`  

6. [CANU](http://canu.readthedocs.io/en/stable/)  

Canu 1.6

Canu is a fork of the Celera Assembler designed for high-noise single-molecule sequencing (such as the PacBio RSII or Oxford Nanopore MinION).

`canu`

7. [minimap/miniasm](https://github.com/lh3/miniasm)  

minimap version 0.2-r124-dirty

miniasm version 0.2-r168-dirty

Miniasm is a very fast OLC-based de novo assembler for noisy long reads.  

`minimap` `miniasm`  

8. [PLATANUS](http://platanus.bio.titech.ac.jp/)  

PLATform for Assembling NUcleotide Sequences

Read more: Kajitani R, Toshimoto K, Noguchi H, Toyoda A, Ogura Y, Okuno M, Yabana M, Harada M, Nagayasu E, Maruyama H, Kohara Y, Fujiyama A, Hayashi T, Itoh T, “Efficient de novo assembly of highly heterozygous genomes from whole-genome shotgun short reads”. Genome Res. 2014 Aug;24(8):1384-95. doi: 10.1101/gr.170720.113. 

*under construction*  

9. [sspace](https://github.com/nsoranzo/sspace_basic)  

SSPACE is a script able to extend and scaffold pre-assembled contigs using one or more mate pairs or paired-end libraries, or even a combination.  

`perl /opt/sspace_basic/SSPACE_Basic.pl`  

10. [Pilon](https://github.com/broadinstitute/pilon/wiki)  

version 1.22

Pilon is a software tool which can be used to (1) automatically improve draft assemblies and (2) find variation among strains, including large event detection.  

`pilon`  

11. [QUAST](http://quast.sourceforge.net/quast.html)

version 4.5

QUAST evaluates genome assemblies

`quast`  

12. [CGAL](https://pachterlab.github.io/cgal/)   

CGAL is a tool for computing genome assembly likelihoods. It computes the likelihood of reads with respect to the assembly and a statistical model which can be used as a metric for evaluating assemblies.  

*unser construction*  

## mapping ##

1. [bowtie2](http://bowtie-bio.sourceforge.net/bowtie2/index.shtml)

version 2.2.6

Bowtie 2 is an ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences.

2. [tophat](https://ccb.jhu.edu/software/tophat/index.shtml)

version 2.1.0

TopHat is a fast splice junction mapper for RNA-Seq reads. Please note that TopHat has entered a low maintenance, low support stage as it is now largely superseded by HISAT2 (32).

3. [bwa](http://bio-bwa.sourceforge.net)

version 0.7.12-r1039

BWA is a software package for mapping low-divergent sequences against a large reference genome, such as the human genome.  

4. [gmap](http://research-pub.gene.com/gmap/src/README)

version 2015-12-31

GMAP: a genomic mapping and alignment program for mRNA and EST sequences

[aligner tutorial](https://github.com/PacificBiosciences/cDNA_primer/wiki/Aligner-tutorial:-GMAP,-STAR,-BLAT,-and-BLASR#refgmap)  

5. [STAR](https://github.com/alexdobin/STAR)

version 2.5.0a

STAR: ultrafast universal RNA-seq aligner

`STAR`  

6. [hisat2](https://ccb.jhu.edu/software/hisat2/index.shtml)  

version 2.1.0

HISAT2 is a fast and sensitive alignment program for mapping next-generation sequencing reads (both DNA and RNA) to a population of genomes (as well as to a single reference genome). 

`hisat2` `hisat2-align-s` `hisat2-align-l` `hisat2-build` `hisat2-build-s` `hisat2-build-l` `hisat2-inspect` `hisat2-inspect-s` `hisat2-inspect-l`


## File processing ##

1. [fastx-toolkit](http://hannonlab.cshl.edu/fastx_toolkit/)

version 0.0.14

The FASTX-Toolkit is a collection of command line tools for Short-Reads FASTA/FASTQ files preprocessing.

2. [seqtk](https://github.com/lh3/seqtk)
 
 version 1.0-r31
 
 Seqtk is a fast and lightweight tool for processing sequences in the FASTA or FASTQ format.
 
 `seqtk`  

3. [bamtools](https://github.com/pezmaster31/bamtools/wiki)

version 2.4.0

Bamtools is a command-line toolkit for reading, writing, and manipulating BAM (genome alignment) files. 

4. [samtools](http://samtools.sourceforge.net)

Version: 0.1.19-96b5f2294a

SAM Tools provide various utilities for manipulating alignments in the SAM format, including sorting, merging, indexing and generating alignments in a per-position format.

[samtools cheatsheet](https://davetang.org/wiki/tiki-index.php?page=SAMTools)

5. [bedtools](http://bedtools.readthedocs.io/en/latest/)

version 2.25.0





