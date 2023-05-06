# msbi-32400-final-project
Call variants on Pevsner autism bam (Web Document 9.7 at http://www.bioinfbook.org/php/ then annotate with snpEff + Clinvar and upload to VEP for ExAC population frequencies. Compare variants in the 101 target gene list with ExAC frequencies expected autism frequencies. Use hg19.fa (see below), not Pevsner's WebDocument_9-6_101autism.fa. Use CDC 2016 frequencies: https://www.cdc.gov/ncbddd/autism/
1.Call variants on Pevsner autism bam
2.Annotate with snpEff + Clinvar and upload (unannotated) VCF to VEP for gnomAD population frequencies.  
3.Compare variants in the 101-target list with ExAC frequencies expected autism frequencies
![image](https://user-images.githubusercontent.com/14998172/236643234-11e04cfe-9bdb-4e74-bf08-483df0498719.png)
DATA
hg19 Human Genome in the 2bit format
the Feb 2017 ClinVar VCF file 
Autisim BAM file
![image](https://user-images.githubusercontent.com/14998172/236643263-30f93519-5f7f-48ca-bab8-5484c63050d7.png)
TOOL
   twoBitToFa
   samtools
   bcftools
   Burrows-Wheeler Aligner(bwa) tool
   snpEFF
![image](https://user-images.githubusercontent.com/14998172/236643274-22bbb346-6ca4-4777-9026-7e9621aa000a.png)
