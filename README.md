# eoe-paper

Additional per-sample and per-subject metadata spreadsheets for 
[Inflammation-associated microbiota in pediatric eosinophilic esophagitis](https://doi.org/10.1186/s40168-015-0085-6)
(SRA BioProject [PRJNA451431], [PMID 26034601]).

`sample_attributes.csv` contains per-sample metadata as uploaded to the [SRA],
plus the SRA accession numbers for each sample (for the SRA BioProject,
BioSample, Study, Sample, and Run).  Five samples were excluded from the SRA
submission as they contained no reads following demultiplexing; the SRA columns
here are blank for these five.

`subject_attributes.csv` contains additional per-subject metadata.  The
Subject column corresponds to the patient column of the sample attributes
spreadsheet.

[SRA]: https://www.ncbi.nlm.nih.gov/sra
[PMID 26034601]: https://www.ncbi.nlm.nih.gov/pubmed/26034601
[PRJNA451431]: https://www.ncbi.nlm.nih.gov/bioproject/451431
