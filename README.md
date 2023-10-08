Neoantigen prediction for the SSM3 oestrogen receptor positive breast cancer mouse model  
Biomedical Science Honours Thesis 2023
Department of Biochemistry, University of Otago. 

This GitHub pages contains the code used for my honours project using SSM3 tumour and matched normal WGS data 
and SSM3 tumour RNA-seq data to predict neoantigens. In summary: 
- The data was pre-processed to generate sorted BAM files that had been aligned to the GRCm39 reference genome. 
- The variant calling tool used was VarScan2.
- The variant VCF was annotated with VEP. 
- pVACseq was used as the neoantigen immunogenicity prediction tool
- Kallisto was used to calculate transcript expression for the neoantigens.
