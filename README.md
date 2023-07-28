# SHIELD-NGS
Description of NGS data analysis
1. We used the Biocluster server (https://help.igb.illinois.edu/Biocluster) provided by the Institute for Genomic Biology (IGB) at the University of Illinois at Urbana-Champaign (UIUC) for NGS data processing and analysis. NGS data files were transferred to the Biocluster using Cybeduck.
2. We used the FASTX-TOOLKIT module available at Biocluster for file conversion (i.e., fastq to fasta) and reads trimming.
3. We used the blastn command in BLAST+ module available at Biocluster for the alignment of NGS reads to library sequences.
4. A sample code for the analysis of "SHIELD_NGS_file-n" is provided in the NGS analysis pipeline.
5. System requirements: analysis was performed in MacOS (13.4.1) Terminal by connecting to IGB Biocluster. Specific dependencies can be found here: https://help.igb.illinois.edu/Biocluster 
