Assembly Improvement
====================
Take in an assembly in FASTA format, reads in FASTQ format, and optionally a reference and produce a better reference using Abacas/SSpace and GapFiller.

[![Build Status](https://travis-ci.org/sanger-pathogens/assembly_improvement.svg?branch=master)](https://travis-ci.org/sanger-pathogens/assembly_improvement)

Scaffolding is performed using SSpace, and gap closing is performed using GapFiller. Both must be downloaded from http://www.baseclear.com
[Optional] Contig Ordering is performed using Abacas, and requires nucmer and promer to be installed.

