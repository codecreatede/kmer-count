# kmerstring-count-graph
- a ruby based version of kmer iterations and kmer graph preparation. It counts the kmers and gives the occurrences. An implementation of the exact match string algorithm. You can use this over the entire fasta by using the File.open(readlines). Saw this code [kmercount](https://github.com/uio-bmi/kmercount) so wrote this.

- run like this and it will output the frequency tables.
```
kmers("AAGAAATGAGAAGTAATCAGAAAACCACTTAAGG", 31)
AAGAAATGAGAAGTAATCAGAAAACCACTTA 1
AGAAATGAGAAGTAATCAGAAAACCACTTAA 1
GAAATGAGAAGTAATCAGAAAACCACTTAAG 1
AAATGAGAAGTAATCAGAAAACCACTTAAGG 1
```
Gaurav Sablok \
University of Potsdam \
Potsdam,Germany
