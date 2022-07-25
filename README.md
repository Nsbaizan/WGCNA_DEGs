# WGCNA_DEGs
This code provides a strategy for improved biomarker discovery from your transcriptomic data. It consists in building a co-expression network from an entire dataset, and only thereafter filtering by DEGs. This method can be applied in transcriptomic studies, regardless of biological system, species or question being considered.
If you are using WGCNA_DEGs in your work, please cite the paper (*link to the paper once it is published*)

# Citation
Sánchez-Baizán, N., Ribas, L., Piferrer, F (2022). "Improved biomarker discovery through a plot twist in transcriptomic data analysis." *insert here info to cite the paper*

Langfelder P, Horvath S (2008). “WGCNA: an R package for weighted correlation network analysis.” BMC Bioinformatics, 559. [Available from here](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-9-559.)

Langfelder P, Horvath S (2012). “Fast R Functions for Robust Correlations and Hierarchical Clustering.” Journal of Statistical Software, 46(11), 1–17. [Available from  here](https://www.jstatsoft.org/v46/i11/.)
    


# Introduction
Since 2005 weighted gene co-expression network analysis (WGCNA) has emerged as a powerful method to explore relationships between genes. However, an approach combining both methods, i.e., filtering the transcriptome dataset by DEGs or other criteria, followed by WGCNA (DEGs+WGCNA), has become common. This is of concern because such approach can affect the resulting underlying architecture of the network under analysis and lead to wrong conclusions. Here, we provide the code for applying WGCNA to exploit entire datasets without affecting the topology of the network, followed the strength and relative simplicity of DEGs analysis (WGCNA+DEGs). The code is based on the previously published [tutorials for WGCNA](https://horvath.genetics.ucla.edu/html/CoexpressionNetwork/Rpackages/WGCNA/Tutorials/) and uses the example with the mouse dataset (Wang et al., 2019, GSE117590) during sex differentiation, at 12.5 and 16.5 days post coitum. 

