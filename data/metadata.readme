(1) Metadata for papers from these sources are combined: CZI, PMC, BioRxiv/MedRxiv. (total records 29500)
	- CZI 1236 records
	- PMC 27337
	- bioRxiv 566
	- medRxiv 361
(2) 17K of the paper records have PDFs and the hash of the PDFs are in 'sha'
(3) For PMC sourced papers, one paper's metadata can be associated with one or more PDFs/shas under that paper - a PDF/sha correponding to the main article, and possibly additional PDF/shas corresponding to supporting materials for the article.
(4)	13K of the PDFs were processed with fulltext ('has_full_text'=True)
(5) Various 'keys' are populated with the metadata:
	- 'pmcid': populated for all PMC paper records (27337 non null)
	- 'doi': populated for all BioRxiv/MedRxiv paper records and most of the other records (26357 non null)
	- 'WHO #Covidence': populated for all CZI records and none of the other records (1236 non null)
	- 'pubmed_id': populated for some of the records
	- 'Microsoft Academic Paper ID': populated for some of the records




2020-03-20
---CHANGES---
* normalized doi, authors, title, abstract strings
* merged redundant rows in metadata file on doi, pmcid, and pubmed_id
* metadata sha column can now include multiple files (some PMC files have multiple associated PDFs)
* added column in metadata file "full_text_file" to signal the tar.gz file in which the full text json resides
---SUMMARY---
total metadata rows: 44220
custom_license: 16959 full text (new: 15533)
noncomm_use_subset: 2353 full text (new: 385)
comm_use_subset: 9118 full text (new: 128)
biorxiv_medrxiv: 885 full text (new: 110)




2020-03-27
---CHANGES---
* added column "cord_uid" (this persistent identifier is a 8-char alphanumeric string unique to each entry)
* added column "url" (URL to paper landing page where available)
* normalized publication date, dois
* adjusted deduplication logic slightly (affects 3 papers)
* removed some entries that correspond to indices or table of contents

---SUMMARY---
total metadata rows: 45774
biorxiv_medrxiv: 1053 full text (new: 194, removed: 26)
comm_use_subset: 9315 full text (new: 210, removed: 13)
custom_license: 20657 full text (new: 4218, removed: 520)
noncomm_use_subset: 2350 full text (new: 6, removed: 9)