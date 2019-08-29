## File name key

### Directory structure of cite_astro_software_2019
+ [API_SEARCH/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/API_SEARCH) - ADS API Search for software aliases
+ [XML_Search/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/XML_SEARCH) - XML Scraping for sofware aliases
+ [READ_ME.md](https://github.com/dbouquin/cite_astro_software_2019/blob/master/README.md)
+ [LICENSE.md](https://github.com/dbouquin/cite_astro_software_2019/blob/master/LICENSE)
+ [File_Name_Key.md](https://github.com/dbouquin/cite_astro_software_2019/blob/master/File_Name_Key.md) - The file you're reading

### [XML_SEARCH/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/XML_SEARCH)
+ [XML_PARSER.py](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_PARSER_082019.py) - Script used to query the AAS XML files
+ [XML_ALIAS_LIST.txt](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_ALIAS_LIST.txt) - List of software aliases searched for using the XML_PARSER.py script
+ [XML_RESULTS/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/XML_SEARCH/XML_RESULTS_082819) - Contains scripts used to analyze results of XML scraping

### [XML_SEARCH/XML_RESULTS/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/XML_SEARCH/XML_RESULTS_082819)
+ [XML_FINAL_ANALYSIS_082819.ipynb](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_FINAL_ANALYSIS_082819.ipynb) - Notebook used to generate results files
+ [XML_CLEAN_INPUT_082019.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_CLEAN_INPUT_082019.csv) - Input file from scraping the XML for software aliases
+ [XML_FINAL_ANALYSIS_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_FINAL_ANALYSIS_082819.csv) - File resulting from initial analysis munging - columns created for bib, ack, fn, and rec_credit
+ [XML_alias_per_paper_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_alias_per_paper_082819.csv) - Number of unique aliases per paper
+ [total_papers_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/total_papers_082819.csv) - Total papers mentioning each software package
+ [mentions_per_journal_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/mentions_per_journal_082819.csv) - Total papers mentioning each software package by journal title
+ [XML_journal_year_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_journal_year_082819.csv) - Total papers mentioning each software package by journal title by year
+ [mentions_per_package_by_journal_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/mentions_per_package_by_journal_082819.csv) - Total papers mentioning each software package by journal title and package name
+ [alias_per_package_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/alias_per_package_082819.csv) - Unique aliases per package
+ [ID_only_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/ID_only_082819.csv) - Count of articles that mentioned software using identifiers per package
+ [non_ID_only_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/non_ID_only_082819.csv) - Count of articles that mentioned software using non-identifiers per package
+ [XML_alias_paper_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_alias_paper_082819.csv) - Count of articles that mentioned software using any alias per package
+ [XML_tags_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_tags_082819.csv) - Unique combinations of nested XML tags for each package
+ [XML_unique_paper_per_year_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/XML_unique_paper_per_year_082819.csv) - Total number of papers mentioning software each year per package
+ [bib_count_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/bib_count_082819.csv) - Total number of papers mentioning software in a bibligraphic entry per package
+ [ack_count_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/ack_count_082819.csv) - Total number of papers mentioning software in an acknowledgement per package (bibliographies are often nested within acknowledgement tags)
+ [fn_count_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/fn_count_082819.csv) - Total number of papers mentioning software in a footnote per package
+ [rec_credit_count_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/rec_credit_count_082819.csv) - Total number of papers mentioning software that gave some form of recognizable credit
+ [rec_credit_only_files_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/rec_credit_only_files_082819.csv) - List of papers that gave a recognizable form of credit
+ [rec_credit_only_files_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/XML_SEARCH/XML_RESULTS_082819/rec_credit_only_files_082819.csv) - List of papers mentioning software that gave no form of recognizable credit

## XML INPUT/RESULTS COLUMN EXPLANATIONS

| Column  | Explanation |
| ------------- | ------------- |
| Alias  | Alias list (See: XML_ALIAS_LIST.txt)  |
| Software_Package  | Name of software package  |
| Identifier  | 1 = alias is identifier. 0 = alias is not identifier.  |
| Pub_Year  | Year of publication ("pub-date" in XML)  |
| DOI  | Digital object identifier  |
| Journal_Title  | Canonical name of the publication the record appeared in ("journal-title" in XML)  |
| Article_ID  | Identifiers associated with the paper ("article-id" in XML)  |
| File_Name  | Name of XML file alias appeared in  |
| Parent1_Tag  |  Layer 1 of XML Tags surrounding alias (See: [NISO JATS Tag Library](https://jats.nlm.nih.gov/publishing/tag-library/1.2/index.html)) |
| Parent2_Tag  |  Layer 2 of XML Tags surrounding alias (See: [NISO JATS Tag Library](https://jats.nlm.nih.gov/publishing/tag-library/1.2/index.html))|
| Parent3_Tag  |  Layer 3 of XML Tags surrounding alias (See: [NISO JATS Tag Library](https://jats.nlm.nih.gov/publishing/tag-library/1.2/index.html))|
| Parent4_Tag  |  Layer 4 of XML Tags surrounding alias (See: [NISO JATS Tag Library](https://jats.nlm.nih.gov/publishing/tag-library/1.2/index.html))|
| Parent1_Content  |  ≥10000 characters between Layer 1 XML Tags (See: XML_PARSER.py) |
| Parent2_Content  |  ≥10000 characters between Layer 2 XML Tags (See: XML_PARSER.py) |
| Parent3_Content  |  ≥10000 characters between Layer 3 XML Tags (See: XML_PARSER.py) |
| Title  | Title of the record ("article-title" in XML) |
| Author(s)  | List of authors on a paper ("name" in XML)  |
| Publisher  | Publisher of the record ("publisher-name" in XML)  |


### [API_SEARCH/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/API_SEARCH)

+ [ADS_API_SEARCH_QUERY.py](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/ADS_API_SEARCH_QUERY.py) - Script used to query the ADS API
+ [API_ALIAS_LIST.txt](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ALIAS_LIST.txt) - List of software aliases searched for using the ADS API
+ [API_ANALYSIS/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/API_SEARCH/API_ANALYSIS_061019) - Contains scripts used to analyze results of API query
+ [API_Cleaner.py](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_CLEANER_031919.py) - Removes confounds from ADS API results

### [API_SEARCH/API_ANALYSIS_082819/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/API_SEARCH/API_ANALYSIS_082819)
+ [API_CLEAN_INPUT_061019.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_CLEAN_INPUT_061019.csv) - Input file from ADS API queries for software aliases
+ [API_FINAL_ANALYSIS_082819.csv]https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_FINAL_ANALYSIS_082819.csv) - File resulting from initial analysis munging - converts highlights to strings
+ [API_FINAL_ANALYSIS_082819.ipynb](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_FINAL_ANALYSIS_082819.ipynb) - Notebook used to generate results files

### [API_ANALYSIS_082819/API_RESULTS_082819/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_082819)
+ [API_alias_citations_082019.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_082819/API_alias_citations_082019.csv) - Software citations per paper
+ [API_alias_paper_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_082819/API_alias_paper_082819.csv) - Aliases per paper
+ [API_cite_aliases_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_082819/API_cite_aliases_082819.csv) - REVISIT THIS
+ [API_over_time_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_082819/API_over_time_082819.csv) - Total mentions of software aliases over time

### [API_RESULTS_AAS_ONLY_082819/](https://github.com/dbouquin/cite_astro_software_2019/tree/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_AAS_ONLY_082819)
+ [API_CLEAN_INPUT_AAS_ONLY_061019.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_CLEAN_INPUT_061019.csv) - Input file from ADS API queries for software aliases (AAS only)
+ [API_FINAL_ANALYSIS_AAS_ONLY_082819.ipynb](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_AAS_ONLY_082819/API_FINAL_ANALYSIS_AAS_ONLY_082819.ipynb) - Notebook used to generate results files (AAS only)
+ [API_alias_citations_AAS_ONLY_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_AAS_ONLY_082819/API_alias_citations_AAS_ONLY_082819.csv) - Software citations per paper (AAS only)
+ [API_alias_paper_AAS_ONLY_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_AAS_ONLY_082819/API_alias_paper_AAS_ONLY_082819.csv) - Aliases per paper
+ [API_cite_aliases_AAS_ONLY_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_AAS_ONLY_082819/API_cite_aliases_AAS_ONLY_082819.csv) - REVISIT THIS (AAS only)
+ [API_over_time_AAS_ONLY_082819.csv](https://github.com/dbouquin/cite_astro_software_2019/blob/master/API_SEARCH/API_ANALYSIS_082819/API_RESULTS_AAS_ONLY_082819/API_over_time_AAS_ONLY_082819.csv) - Total mentions of software aliases over time (AAS only)


## API INPUT/RESULTS COLUMN EXPLANATIONS
Refer to [Comprehensive List of Solr Fields & Operators](http://adsabs.github.io/help/search/comprehensive-solr-term-list) for the complete list of methods of querying the ADS system.


| Column  | Explanation |
| ------------- | ------------- |
| Alias  | Alias list (See: API_ALIAS_LIST.txt)  |
| Software_Package  | Name of software package  |
| Identifier  | 1 = alias is identifier. 0 = alias is not identifier.  |
| Highlight  | ≥150000 character snippet around alias. (See: ADS_API_SEARCH_QUERY.py)  |
| Citation  | TRUE = In-text citation used. FALSE = In-text citation not used. |
| Bibcode  | ADS identifier of a paper  |
| Alternate_Bibcode  | List of alternate bibcodes for that document  |
| BibGroup  | Bibliographic group that the bibcode belongs to (curated by staff outside of ADS)  |
| Publisher  | Canonical name of the publication the record appeared in  |
| Article_ID  | Abstract field used to search an array of alternative identifiers for the record. May contain alternative bibcodes, DOIs and/or arxiv ids.  |
| DOI  | Digital object identifier  |
| Pub_Year  | Year of publication  |
| Pub_Date  | Date of publication (YYYY-MM-DD)  |
| Author  | List of authors on a paper  |
| Title  | Title of the record  |
