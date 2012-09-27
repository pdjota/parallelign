parallelign
===========

A series of scripts to align Genome Analyzer Data with existing Genomes using  Cloud Bio Linux (http://cloudbiolinux.org/).

Asumming a data sample produced from GAxII (FASTA or FASTQ) and a known genome, i.e.: hg.19

It will produce a SAM file of the matching reads. It will allow user to benchmark processes according to paralelization level.

Requirements
------------

Amazon WS account, able to create S3 volumnes and start EBS instances.

[Example Gist][1]
[1]: https://gist.github.com/3724117


Further work
------------

  - Create new AMI.
  - Visualization with SAM tools.