### This repo contains a list of Alzheimer's Disease (AD) and Parkinson's Disease (PD) associated SNPs and a script/guide to extend and map those snps to genes called SNPs_Genes_Mapping.ipynb.

 - AD_SNPS.txt -> Alzheimer's Disease associated SNPs extracted from PheWAS and DisGeNet (curated only).
 - PD_SNPS.txt -> Parkinson's Disease associated SNPs extracted from PheWAS and DisGeNet (curated only).

 - SNPs_Genes_Mapping.ipynb -> Script Guide that takes the above mentioned seed SNPs and extends those with LD associated SNPs using Haploreg (4.1) and eQTLs from GTex Portal
 - Mechanism_Mapping -> Script that loads the NEUROMMSIG Mechanisms to Genes Mapping and concatenates the SNPS-Genes Mapping from above with the Mechanisms 

For further questions please contact me: thomas.lordick@scai-extern.fraunhofer.de

Best,

Thomas
