# [`amplify`](https://owncloud.gwdg.de/index.php/s/fZ9sgG507Mx0xV3)
Use a pair of primers to find corresponding amplicon sequences in
genomes. Exact matches only.

## Compile
Given that you have `git`, `golang`, and `make`:

      git clone https://github.com/IvanTsers/intersect
      cd intersect
      make

## Basic usage
   amplify -p pair_of_primers.fasta genome1.fasta genome2.fasta ...