# fasta_cleaner
fasta_clean.py, for cleaning fasta files.

This script will remove all contigs that have coverage below 5 or lengths below 500 bp.

It will also scan the beginning and the end of each contig for garbage sequences, for example, a sequence ending in ...GAGCTAGCTGGCTTGAGCTACGTGAGTCTACTGACTACTTTTACTACTAAAAAAAAAAAAAAAAAAAATAAAAAAAAAAAAAAAAAAAAAAAAAAATAAAAAAAAAAAAAAAAAAAAAAAATAAAAA would be trimmed to ...GAGCTAGCTGGCTTGAGCTACGTGAGTCTACTGACTACTTTTACTACT

Usage:

python fasta_clean.py [source_directory] [destination_directory]
