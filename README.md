Download Link: https://assignmentchef.com/product/solved-qbio401-assignment2
<br>
Four FASTQ files are placed on Blackboard:

XI1_ATCACG_L001_R1_001.fastq

XI1_ATCACG_L001_R2_001.fastq

RETT-1_S1_L001_R1_001.fastq

RETT-1_S1_L001_R2_001.fastq

These are next generation sequencing files from a paired-end run. The XI1 reads are mostly 250 base pairs long, the RETT reads are mostly 150 base pairs long. Complicating the assignment, there are a few reads that are a few bases shorter or longer than 250 or 150.

<ol>

 <li>Write a Python function that counts the number of reads with the same, shorter and longer length than expected. For each of the four files print the out. Compare the results and describe your finding [3pt].</li>

</ol>




<ol start="2">

 <li>Write a Python function that for each of the positions 1 to 250 (or 1 to 150) will compute the fraction of reads in the file with quality scores greater than or equal to 30 at that position. For each of the four files plot the output. Compare the results and describe your finding [5pt].</li>

</ol>




<ol start="3">

 <li>Write another function that for k from 0 to 250 (or from 0 to 150) will count the number of reads in the file with exactly k positions with quality scores greater than or equal to 30. For each of the four files plot the output [Bonus 2pt].</li>

</ol>




For the plots, please use the package matplotlib.pyplot mentioned in the class.