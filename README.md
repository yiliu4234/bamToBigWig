# bamToBigWig
In order to view the genome coverage in UCSC , bamToBigWig transforms the bam file to BigWig 
* The bamfile should be sorted.
* Internally the script calls bamtools，so the bamtools should be dwonlad and on the PATH.
* usage:</br>
```bamToBigWig input.bam output.bw```
