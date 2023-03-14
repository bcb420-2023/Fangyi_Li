# Docker inheritance
FROM risserlin/bcb420-base-image:winter2023

# Install DESeq2 package
RUN R -e 'BiocManager::install(c("DESeq2"))'

# Install pheatmap package
RUN R -e "install.packages(c('pheatmap'), dependencies=TRUE, repos='http://cran.rstudio.com/')"
