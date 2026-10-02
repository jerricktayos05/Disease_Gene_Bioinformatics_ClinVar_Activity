# Bioinformatics Lab Activity: Exploring FGFR3 and Achondroplasia

- **Name:** Jerrick Paul T. Tayos
- **Assigned Gene:** FGFR3
- **Associated Disease:** Achondroplasia
- **Genome Assembly:** GRCh38/hg38
- **Date Completed:** October 1, 2026

- ## UCSC Gene Location

- **Official Gene Symbol:** FGFR3
- **Full Gene Name:** Fibroblast growth factor receptor 3
- **Chromosome:** Chromosome 4 (band 4p16.3)
- **Genome Assembly Used:** GRCh38/hg38
- **Genomic Coordinates Shown in UCSC:** chr4:1,793,293-1,808,867
- **DNA Strand:** - (Minus / Negative strand)
- **Approximate Gene Size or Length:** 15,575 bp (~15.6 kb)

<img width="1365" height="767" alt="Screenshot 2026-10-02 075601" src="https://github.com/user-attachments/assets/f17a837d-dfc8-4a35-8ac1-96917406f002" />
Figure 1: Genomic location and region of the FGFR3 gene displayed in the UCSC Genome Browser (GRCh38/hg38).

## Exons, Introns, and Transcripts

- **Selected Transcript:** NM_000142.5 (RefSeq Curated canonical transcript)
- **Number of Exons Identified:** 6 exons visible in this zoomed view (out of 19 total full-length canonical exons across FGFR3)
- **Multiple Transcripts/Isoforms Visible:** Yes, multiple transcript isoforms are clearly visible in both GENCODE V50 and NCBI RefSeq tracks (e.g., NM_022965.4, NM_000142.5, NM_001354810.2), showing alternative exon boundaries and splicing.
- **Exon vs. Intron Definition:** Exons are the sequences represented by thick colored blocks retained in mature mRNA that contain protein-coding regions and UTRs, whereas introns are non-coding intervening regions represented by horizontal lines with directional arrows (`<<<`) that are spliced out during pre-mRNA processing.
- **Relative Length Comparison:** Introns span significantly longer genomic distances than the exon blocks across the FGFR3 gene structure.

<img width="1365" height="767" alt="Screenshot 2026-10-02 080346" src="https://github.com/user-attachments/assets/706720c4-4c8a-4fa8-a1d6-f0286d0f0cf5" />
Figure 2: Zoomed-in view of the exon-intron structure and transcript isoforms of FGFR3 in UCSC Genome Browser.

## UCSC Annotation Tracks

- **Gene Annotation Track Used:** NCBI RefSeq Curated / GENCODE V50
- **ClinVar Variant Visibility:** Yes, multiple ClinVar variant markers are visibly distributed across and near the coding regions of the FGFR3 gene.
- **Conservation Observations:** The UCSC 100 Vertebrates conservation track shows high conservation scores (peaks) corresponding primarily to the coding exon regions, whereas intronic regions demonstrate lower conservation scores.
- **Biological Importance of Conservation:** Strong evolutionary conservation across 100 vertebrate species indicates that natural selection has preserved these specific nucleotide sequences over millions of years. Mutations in these highly conserved regions are much more likely to disrupt essential protein structure or function, leading to pathogenic traits.

<img width="1365" height="767" alt="Screenshot 2026-10-02 081115" src="https://github.com/user-attachments/assets/337671fd-ef38-4839-b445-7a742b2708e6" />
Figure 3: Display of ClinVar clinical variants and UCSC 100 Vertebrates conservation tracks across the FGFR3 gene in UCSC Genome Browser.

## Selected ClinVar Variant

- **Gene:** FGFR3
- **Variant Name / HGVS Description:** NM_000142.5(FGFR3):c.1138G>A (p.Gly380Arg)
- **rsID / ClinVar Variation ID / VCV Accession:** Variation ID: 16328 | VCV Accession: VCV000016328.32 | rsID: rs28931614
- **Chromosome and Genomic Position:** Chromosome 4, chr4:1,799,517 (GRCh38)
- **Associated Condition / Disease:** Achondroplasia
- **Clinical Significance:** Pathogenic
- **Review Status:** Reviewed by expert panel
- **ClinVar Record URL:** https://www.ncbi.nlm.nih.gov/clinvar/variation/16328/

<img width="1365" height="767" alt="Screenshot 2026-10-02 081813" src="https://github.com/user-attachments/assets/4ce53b1c-ecbe-4ed8-9326-d8a099982bd6" />
Figure 4: NCBI ClinVar detail record for the pathogenic c.1138G>A (p.Gly380Arg) variant associated with Achondroplasia.

## Locating the Variant in UCSC

- **Location Relative to Gene:** The c.1138G>A variant is located directly within a coding exon (Exon 9 in canonical transcript NM_000142.5) of the FGFR3 gene.
- **Region Type:** Exon (Coding region).
- **Coding vs. Non-Coding:** Coding region.
- **Predicted Effect on Gene/Product:** It causes a gain-of-function missense mutation (p.Gly380Arg) in the transmembrane domain of the FGFR3 receptor, leading to constitutive (overactive) receptor signaling that restricts chondrocyte differentiation and bone elongation.
- **Additional Evidence Needed for Pathogenicity:** Functional cell-based kinase assays, population frequency data from gnomAD, co-segregation analysis in multigenerational families, and knock-in animal models.

<img width="1353" height="767" alt="Screenshot 2026-10-02 082600" src="https://github.com/user-attachments/assets/29db68be-7a11-4bad-91fb-174450f9d94a" />
Figure 5: Zoomed-in UCSC Genome Browser view showing the c.1138G>A variant marker aligned with the coding exon of FGFR3.

## Reflection

1. **UCSC Genome Browser Insights:** The UCSC Genome Browser provided a dynamic, visual map of the FGFR3 gene's physical layout, showing exact exon-intron proportions and alternative splice isoforms that cannot be fully appreciated from reading text descriptions alone. It clearly demonstrated how short coding exons are separated by large non-coding introns across the genomic region.
2. **Value of Exact Genomic Coordinates:** Knowing the exact genomic coordinates of a disease variant is essential for precisely mapping mutations across different genome assembly builds and designing targeted diagnostic tools such as PCR primers, sequencing panels, or CRISPR guide RNAs. It ensures unambiguous communication of variant positions across global clinical databases.
3. **Limitations of Location-Based Predictions:** Predicting a variant's functional impact based solely on genomic location is limited because identical regions can have different biological consequences depending on local chromatin structure, tissue-specific splicing, or conservative amino acid substitutions that preserve protein structure. Additionally, non-coding intronic mutations may silently alter regulatory elements or splice sites that standard positional mapping might overlook.
4. **Most Interesting Feature Observed:** The most striking feature observed was the dense concentration of pathogenic ClinVar single-nucleotide variants clustered within specific coding exons responsible for encoding the transmembrane and kinase domains of the FGFR3 protein. It highlights how critical specific structural domains are to normal bone development and receptor regulation.

5. ## References and Links

- **UCSC Genome Browser:** [https://genome.ucsc.edu/](https://genome.ucsc.edu/)
- **UCSC Genome Browser Tutorials:** [https://genome.ucsc.edu/docs/tutorials/](https://genome.ucsc.edu/docs/tutorials/)
- **UCSC Genome Browser 101 Tutorial:** [https://genome.ucsc.edu/docs/tutorials/gb101.html](https://genome.ucsc.edu/docs/tutorials/gb101.html)
- **NCBI ClinVar Database:** [https://www.ncbi.nlm.nih.gov/clinvar/](https://www.ncbi.nlm.nih.gov/clinvar/)
- **NCBI ClinVar Search Help:** [https://www.ncbi.nlm.nih.gov/clinvar/docs/help/](https://www.ncbi.nlm.nih.gov/clinvar/docs/help/)
- **Selected ClinVar Variant Record (c.1138G>A, VCV000016328):** [https://www.ncbi.nlm.nih.gov/clinvar/variation/16328/](https://www.ncbi.nlm.nih.gov/clinvar/variation/16328/)
