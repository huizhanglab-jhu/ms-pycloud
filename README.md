# MS-PyCloud

MS-PyCloud is a comprehensive software for mass spectrometry-based proteomics data analysis, encompassing peptide identification, protein inference, and quantitation of proteins, phosphosites, and glycan-specific glycopeptides. It processes raw Thermo LC-MS/MS data converted to mzML format, performing searches using GPQuest for glycan databases and MS-GF+ for protein databases, with results filtered based on PSM-level false discovery rates. Protein inference utilizes a bipartite graph analysis algorithm to group significant PSMs, assigning shared peptides to the most supported proteins. Quantitation supports various isobaric tags, including iTRAQ4, iTRAQ8, TMT10, TMT11, TMT16, and TMT18, and employs median normalization for accurate abundance, intensity, and Log2 ratios calculations. Enhancements like SQLite databases for peptide fragment indexing, Numba for JIT compilation, and a Streamlit GUI improve performance and usability. Integrated with AWS for scalable cloud computing, MS-PyCloud ensures efficient and high-availability peptide analysis.


## Preprint and Software

For those interested in our research and preliminary findings, the preprint manuscript is available for review. You can find the document at the following link:

- [Preprint Manuscript on bioRxiv](https://www.biorxiv.org/content/10.1101/320887v1)

### Software Availability
Latest release:
A release version of **MS-PyCloud** with electron UI is ready in the releases section. 06/12/2024

### [Download](https://github.com/huizhanglab-jhu/ms-pycloud/releases/tag/v3.1.0-alpha)

## Contact Us

For any further inquiries or feedback, please don't hesitate to contact us via email at [yhu39@jhmi.edu](mailto:yhu39@jhmi.edu). Your input is invaluable to us as we strive to improve **ms-pycloud** and its supporting documentation.

## References

### Software Tools
- Toghi Eshghi, S.; Shah, P.; Yang, W.; Li, X.; Zhang, H. GPQuest: A Spectral Library Matching Algorithm for Site-Specific Assignment of Tandem Mass Spectra to Intact N-glycopeptides. Anal Chem 2015, 87 (10), 5181-5188. DOI: 10.1021/acs.analchem.5b00024
- Adusumilli, R.; Mallick, P. Data Conversion with ProteoWizard msConvert. Methods Mol Biol 2017, 1550, 339-368. DOI: 10.1007/978-1-4939-6747-6_23.
- Kim, S.; Pevzner, P. A. MS-GF+ makes progress towards a universal database search tool for proteomics. Nat Commun 2014, 5 (1), 5277. DOI: 10.1038/ncomms6277.
- Sun, S.; Hu, Y.; Ao, M.; Shah, P.; Chen, J.; Yang, W.; Jia, X.; Tian, Y.; Thomas, S.; Zhang, H. N-GlycositeAtlas: a database resource for mass spectrometry-based human N-linked glycoprotein and glycosylation site mapping. Clin Proteomics 2019, 16 (1), 35. DOI: 10.1186/s12014-019-9254-0.
- Ma, Z. Q.; Polzin, K. O.; Dasari, S.; Chambers, M. C.; Schilling, B.; Gibson, B. W.; Tran, B. Q.; Vega-Montoto, L.; Liebler, D. C.; Tabb, D. L. QuaMeter: multivendor performance metrics for LC-MS/MS proteomics instrumentation. Anal Chem 2012, 84 (14), 5845-5850. DOI: 10.1021/ac300629p.

### Algorithm
- Zhang, B.; Chambers, M. C.; Tabb, D. L. Proteomic parsimony through bipartite graph analysis improves accuracy and transparency. J Proteome Res 2007, 6 (9), 3549-3557. DOI: 10.1021/pr070230d.
- Ma, Z. Q.; Dasari, S.; Chambers, M. C.; Litton, M. D.; Sobecki, S. M.; Zimmerman, L. J.; Halvey, P. J.; Schilling, B.; Drake, P. M.; Gibson, B. W.; Tabb, D. L. IDPicker 2.0: Improved protein assembly with high discrimination peptide identification filtering. J Proteome Res 2009, 8 (8), 3872-3881. DOI: 10.1021/pr900360j.
- Patro, R.; Kingsford, C. Predicting protein interactions via parsimonious network history inference. Bioinformatics 2013, 29 (13), i237-246. DOI: 10.1093/bioinformatics/btt224.

