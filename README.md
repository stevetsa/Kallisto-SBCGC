# Kallisto-SBCGC

##Running Kallisto on Seven Bridges CGC
kallisto is a program for quantifying abundances of transcripts from RNA-Seq data, or more generally of target sequences using high-throughput sequencing reads. 
<br>Nicolas L Bray, Harold Pimentel, Páll Melsted and Lior Pachter, Near-optimal probabilistic RNA-seq quantification, Nature Biotechnology 34, 525–527 (2016), doi:10.1038/nbt.3519\
<br><br>
Running Kallisto quantification (kallisto quant) using test files that came with the installation
kallisto quant -i transcripts.index -o temp reads_1.fastq.gz reads_2.fastq.gz
