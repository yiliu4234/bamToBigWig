# bamToBigWig
In order to view the genome coverage in UCSC , bamToBigWig transforms the bam file to BigWig 
* The bamfile should be sorted.
* Internally the script calls bamtools and bedGraphToBigWig，so the bamtools and bedGraphToBigWig should be dwonlad and on the PATH.
* genomesize is genoemsize file which includes all chrom size ,can be dowload from UCSC.
* usage:</br>
```bamToBigWig input.bam genomesize output.bw```
