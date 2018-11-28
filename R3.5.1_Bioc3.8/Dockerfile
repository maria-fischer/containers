# Use Bioconductor version 3.8 based on R version 3.5.1
# Documentation: http://bioconductor.org/help/docker/
FROM bioconductor/release_core2:R3.5.1_Bioc3.8

# Install R packages
ADD install.R /tmp/
RUN R -f /tmp/install.R

