# breast-cancer-transcriptomics

Key Implications from Chimera Transcriptomics Analysis
1. High Noise, Some Signal
    Frequent fusions involve pseudogenes or unannotated loci, likely artifacts, but known cancer genes like TYMS and NAIP suggest real events exist and require careful filtering.
2. Dominant Isoforms at Breakpoints
    High isoform fractions (~0.78) show most fusions are driven by a single transcript isoform, suggesting structured splicing or mapping bias.
3. Confidence Score ≠ Read Count
    Very weak correlation between score and spanning reads (r ≈ 0.04) means scores reflect model features beyond raw support—interpret in context.
4. Short Genomic Distance = Cis Events
    Most breakpoints are close together, suggesting read-throughs or intragenic fusions. Long-distance events could reflect true translocations.
5. Cluster Size Uninformative
    Confidence score varies widely across cluster sizes. Even singleton clusters can have high-quality fusions—cluster size alone is not a filter.
6. Correlated Isoform Usage
    5' and 3' isoform fractions are strongly correlated (r ≈ 0.83), implying consistent isoform bias and potentially stable fusion transcripts.
7. Low Fragment Support for Many Fusions
    Many junctions have few supporting reads, indicating either low expression or spurious detection—external validation is needed.

Project Resources
Dataset Webpage: [GEO Accession GSE58135](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE58135)
Direct Download (Expression Matrix): 
  [FTP Link to GSE58135 Matrix Files](https://ftp.ncbi.nlm.nih.gov/geo/series/GSE58nnn/GSE58135/matrix/)
