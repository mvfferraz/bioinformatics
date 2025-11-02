# Genomics Module - Lesson 1

**Study:**  
*Genomic surveillance elucidates Ebola virus origin and transmission during the 2014 outbreak*  
Science, 2014. [DOI: 10.1126/science.1259657](https://doi.org/10.1126/science.1259657)

**Objective:**  
Learn how to download raw genomic sequencing data from NCBI and perform initial quality checks, using a real-world Ebola virus outbreak dataset.

**Dataset:**  
- BioProject accession: PRJNA257197  
- Sample example: SRR1972877  
- Data types: Whole genome sequencing (WGS)  
- Sequencing platform: Illumina HiSeq

**Steps for this lesson:**  
1. **Access the data**  
   - Use [SRA Explorer](https://sra-explorer.info) and NCBI to find the BioProject.
2. **Select samples**  
   - Choose samples of interest (e.g., SRR1972877) and add to collection.
3. **Download data**  
   - FastQ files via URLs or Bash script.  
   - Metadata table (.tsv) for sample information.
4. **Prepare data for quality analysis**  
   - Verify file integrity, organize files, and check metadata.
5. **Next steps:**  
   - Perform quality assessment using tools like FastQC or MultiQC.  

**Notes:**  
This lesson demonstrates practical steps for genomic data retrieval, organization, and quality control, all based on a real published outbreak study.
