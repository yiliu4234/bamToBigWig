# bamToBigWig
In order to view the genome coverage in UCSC , bamToBigWig transforms the bam file to BigWig 
* The bamfile should be sorted.
* Internally the script calls samtools and bedGraphToBigWig，so the samtools and bedGraphToBigWig should be download and on the PATH.
* The genomesize is genoemsize file which includes all chrom size ,can be dowload from UCSC.
* usage:</br>
```bamToBigWig input.bam genomesize output.bw```
