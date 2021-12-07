The zip-file contains three datasets:

# KaggleNews

- Dropped columns Kategorie, Quelle and Art and removed duplicates from the news.csv
- for information on the dropped columns, have a look at the "raw" dataset folder and the news.csv dataset

# GermanFakeNC

- Crawled through its URL column entries to receive and add title and body from each samples URL to the dataset

# GFNC_KaggleNews_merged

- Merged both datasets, creating a new dataset consisting of columns: src_id, url, title, text, date, fake, src_name
- important to note is that the formerly fine grained labels of GermanFakeNC (0.1-1.0) have all been turned into 1, as they all contain some fake information, despite label 0.1 representing "no disinformation in text" as declared by the author of the dataset
- for more information, have a look at the readme of the "raw" dataset folder

