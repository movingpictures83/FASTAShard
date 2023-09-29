# FASTAShard
# Language: Python
# Input: TXT
# Output: DIR
# Tested with: PluMA 1.1, Python 3.6

PluMA plugin to split a FASTA file into shards.

The plugin takes as input a tab-delimited file of keyword-value pairs:
fastafile: Input FASTA
partitions: Number of shards
affix: File suffix
version: Ensembl version

Shards will be sent to user-specified folder.

