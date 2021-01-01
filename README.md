# Detect-Cancer-Cells

## Motivation (Credit to https://www.kaggle.com/c/ucla-stats101c-lec3/data)

Cancer is a group of diseases involving abnormal cell growth with the potential to invade or spread to other parts of the body. The majority of cancers are due to genes mutations, which are permanent alterations in the DNA sequence that makes up a gene. Such mutations can be inherited or caused by environmental and lifestyle factors. Two of the cancer driver genes, which are genes that play a role in cancer, are oncogenes and tumor suppressor genes.

Oncogenes (OGs) are genes that normally help cells grow. When an oncogene mutates or changes, it can become a "bad" gene in the sense that it can become permanently turned on or activated when it is not supposed to be. When this happens, the cell grows out of control and can lead to cancer. Tumor suppressor genes (TSGs) are normal genes that slow down cell division, repair DNA mistakes, or tell cells when to die (a process known as apoptosis or programmed cell death). When tumor suppressor genes do not work properly, cells can grow out of control and can lead to cancer too. The OGs and TSGs work together to keep the balance between cell growth and apoptosis. However, when key genetic alterations accumulate, this balance is disrupted and cancer will happen.

Discovery of cancer driver genes, including OGs and TSGs, is imperative for cancer prevention, diagnosis, and treatment. The project aims to separate OGs and TSGs from neutral genes(NGs) by applying a variety of machine learning models.

## Data Description (Credit to https://www.kaggle.com/c/ucla-stats101c-lec3/data)

The training data are in the file training.csv. In the dataset, each row corresponds to a gene and each column to a feature of the genes. The dataset includes 3,177 genes and 97 predictors, which can be generally categorized as follows: mutation-related features (for example, ratio of mutations), genomic features (for example, gene length), phenotype features (for example, gene expression level) and epigenetic features (which are related with some inheritable phenotype which do not involve alterations in the DNA sequence). A detailed description of each of the 97 predictors is included in the supplementary file Feature_description.xlsx.

This training data includes the responses in the column labeled class. The values of the response are the true class of each gene in the training set: NG (labeled as 0), OG (1) and TSG (2). The id column in this dataset identifies each observation in the training data.

The test data are in file test.csv. The dataset includes 1,363 genes and 97 predictors. The test data does not include the gene classes. The challenge is to correctly identify the OGs and TSGs in this dataset. The id column in this dataset identifies each observation in the test data. To avoid confusions, the values in the id column in the test.csv file are different from those in the training.csv file.
