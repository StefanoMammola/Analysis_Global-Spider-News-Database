# Analysis_Global-Spider-News-Database

R code to generate the analyses about global representation of spiders in the online media.

Full details on the analysis are in:

Mammola S., et al. (2022) An expert-curated global database of online newspaper articles on spiders and spider bites. Scientific Data, DOI: 10.1038/s41597-022-01197-6

Data -------------------------------------

To run the analysis, one should download from figshare the database ~Data_spider_news_global.csv (doi:10.6084/m9.figshare.14822301). See Figshare entry for metadata


Repository contains ----------------------

~Analysis_Data_spider_news_global: R code to generate the analysis.

~Data_spider_news_global_AfterValidation (.csv): The same database as Data_spider_news_global, but after the quality check. Needed to calculate Cohen's kappa.

~Data_spider_news_global_BeforeValidation (.csv): The same database as Data_spider_news_global, but before the quality check. Needed to calculate Cohen's kappa.

~Danger_symbol: Silhouette (.png) used in Figure 3.
