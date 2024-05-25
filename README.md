EXPORTING ENVIRONMENTS\
Recommendation: Name the export file “environment.” Environment name will be preserved.\
Cross-platform compatible:\
conda env export --from-history>ENV.yml

IMPORTING ENVIRONMENTS\
Tip: When importing an environment, conda resolves platform and package specifics.\
From a .yml file:\
conda env create -n ENVNAME --file ENV.yml
