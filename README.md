![alt text](https://github.com/grusso98/gut-microbiota-diet/blob/main/img/biosciences_banner.png)
### Authors:
  <div align="center">
    <p>Gaetano Chiriaco</p>
    <a href="https://www.linkedin.com/in/gaetano-chiriaco-68085820b/" style="text-decoration:none;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/640px-LinkedIn_logo_initials.png" width="2%" alt="" /></a>
  </div>
  
  <div align="center">
    <p>Gianmarco Russo</p>
    <a href="https://www.linkedin.com/in/grusso98/" style="text-decoration:none;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/640px-LinkedIn_logo_initials.png" width="2%" alt="" /></a>
  </div>
<br>
<br>

Data Science MSc @ University of Milan-Bicocca.
Part of the Data science lab in biosciences exam.

# Gut microbiota analysis in relation to different specialized diets

- *EDA.ipynb* contains all the exploratory data analysis on the american gut microbiome dataset, with all the filters used to select our sample.

- *otu_analysis.ipynb* contains the analysis with Qiime:
  -  creation of the metadata,
  -  retrieval of the otu table,
  -  merge of the otu table with our selected samples
  -  Qiime pipeline (trees, core metrics)

- *tax_analysis.ipynb* contains all the taxonomic analysis:
  - taxonomy coverage overview of the sample
  - pyhlum analysis in the sample
  - pyhlum analysis in relation to refined sugar consumption

- *LDA.ipynb* contains the Topic modeling performed on pubmed papers(with 2 and 4 topics):
  - queries with the word 'human' 
  - queries without the word 'human'
 
- *text_extraction-ipynb* contains the code to download the papers analyzed in the LDA notebook 
- htmls contain the visualizations created with pyLDAvis easily accessible through the github page: https://grusso98.github.io/gut-microbiota-diet/
