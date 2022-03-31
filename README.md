# Comics as Data: North America

Collection as Data: North America is a data set drawn from MSU Library Comics Art Collection metadata. Home to the world’s largest comic book collection, developing cataloging metadata as a corpus to query issues of community and representation inspired this project. This dataset holds the opportunity to investigate hidden themes, locality, form, and aesthetics in North America comic culture.

The raw data are located at MARC_data_raw folder as .csv files. For column headings explanation, see column_headings.md.

# Data Documentation

# What we did

## Cleaning

This data was cleaned using Google Sheets and OpenRefine. Particular attention was paid to location, dates, and publishers.
For more information about how the data was cleaned, see cleaning_decisions.md

## Reconciling

We used Wikidata's reconciling service to match our publisher data to pages on wikidata. This allows us to track which comics were published by the same publisher regardless of name changes.

# What files are what
comics_as_data_north_america_2020-01-20_Cleaned.csv is the cleaned dataset, but does not include any reconciliation data. 
comics_as_data_north_america_2020-01-20_reconciled_full.csv is the cleaned data with the reconciled values and QIDs.
comics_as_data_north_america_2020-01-20_reconciled_full.openrefine.tar.gz is a copy of the OpenRefine project, which includes the cleaned data and all reconciliation data. 

# How can I contribute?
We encourage you to download the dataset, work with it, and share the results.
# Team

- Scout Calvert
- Julian Chambliss
- Devin Higgins
- Ranti Junus
- Kristen Mapes
- Kate Topham
