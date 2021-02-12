# git_RBioSNPAS
An R package for variant calling QC-downstream analysis and association study.

Installation:

  - Install devtools
  
        install.packages("devtools")
    
  - Install bioconductor
  
        if (!requireNamespace("BiocManager"))
            install.packages("BiocManager")
            
        BiocManager::install()
    
  - Install stable release
  
        devtools::install_github("jzhangc/git_RBioSNPAS/RBioSNPAS", repos = BiocManager::repositories())    

  - Install development build
  
        devtools::install_github("jzhangc/git_RBioSNPAS/RBioSNPAS", repos = BiocManager::repositories(), ref = "beta")  
        

Update log

    0.0.1 (Feb.12.2021)
      - Initial commit