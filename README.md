# HOW I WOULD EXPLORE THE USE OF TRASTUZUMAB AND BEVACIZUMAB ANTIBODY THERAPIES IN ADDITIONAL CANCER CELLS

I am exploring it from 3 different lens, from that of a biologist, computational biologist and biotechnologist, each lens having their own peculiar key scientific questions.

## Key Scientific Questions:

### Biology lens
1.	What is scRNA-seq? 
	scRNA-seq stands for single-cell RNA sequencing. It's a powerful technique that measures the gene expression (activity) in individual cells. This provides a detailed picture of the cell types and their activity within a tumor sample.

2.	What are HER2 and VEGF?  
	HER2 (human epidermal growth factor receptor 2) is a protein that promotes cell growth. Overexpression of HER2 is linked to some cancers like breast and gastric.
	VEGF (vascular endothelial growth factor) helps create new blood vessels. Tumors rely on these vessels for growth, making VEGF a target in cancer therapy.

3.	How do Trastuzumab and Bevacizumab work?  
	Trastuzumab is a monoclonal antibody that binds to HER2 on cancer cells, blocking its growth-promoting signals.
	Bevacizumab targets VEGF, preventing it from stimulating new blood vessel formation that would feed the tumor.


### Computational Biology lens
1.	How can I analyze scRNA-seq data?  
	Analyzing scRNA-seq data requires specialized software. I can explore user-friendly platforms like GEO (Gene Expression Omnibus) to access pre-processed scRNA-seq datasets and tutorials.

2.	What are gene expression levels?
	Gene expression refers to how active a gene is. scRNA-seq measures the amount of messenger RNA (mRNA) produced by each gene, reflecting its activity level.

3.	How can I identify cancer cell subpopulations?
	scRNA-seq data can reveal different cell types within a tumor. Researchers use clustering algorithms to group cells with similar gene expression patterns, potentially identifying distinct subpopulations.

### Biotechnology lens
1.	What are antibody therapies? 
	Antibody therapies are drugs that harness the immune system. Monoclonal antibodies are lab-made antibodies designed to target specific proteins like HER2 or VEGF.

2.	What are the challenges of developing new cancer therapies? 
	Many steps are involved, including pre-clinical and clinical trials. Challenges include ensuring efficacy, minimizing side effects, and finding therapies effective for specific cancer subtypes.

## Exploring Antibody Therapies in New Cancers:
1.	HER2 and VEGF Expression: Analyze scRNA-seq data from cancer cell lines of other cancers (besides the current approved uses). Do they express high levels of HER2 or VEGF?

2.	Cancer Cell Subpopulations: Are there specific subpopulations within these cancer cell lines that show high expression of HER2 or VEGF?

3.	Correlation with Clinical Data: If available, link the scRNA-seq data with existing patient data. Is there a connection between HER2/VEGF expression and clinical outcomes?

## What are cancer cell lines and why do we use them?

### Cell Lines:

Cell lines are cultured cells grown in a lab. They are widely used in cancer research for several reasons:
*	Accessibility: They are readily available and can be easily manipulated for experiments.
*	Simplicity: They offer a controlled environment, unlike the complex tumor microenvironment in a patient.
*	Reproducibility: Experiments can be repeated with consistent results, facilitating study design.
*	Cost-effectiveness: They are relatively inexpensive compared to using patient samples directly.

#### Limitations of Cell Lines:
*	Non-representative: Cell lines may not perfectly reflect the complexity of human tumors.
*	Genetic Drift: Over time in culture, cell lines can accumulate genetic changes that differ from the original tumor.

All these are the key scientific questions inquired from 3 distinct yet interconnected lenses. This is my approach.

## REFERENCES

1. [What is scRNA-seq?](https://www.nature.com/articles/nprot.2009.236)
2. [What are HER2 and VEGF?](https://pubmed.ncbi.nlm.nih.gov/17883287/#:~:text=Both%20EGFR%20and%20HER2%20are%20targets%20found%20on,a%20target%20that%20acts%20in%20the%20tumour%20microenvironment.)
3. How do Trastuzumab and Bevacizumab work?
[Trastuzumab](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7191090/)
[Bevacizumab reference](https://www.nejm.org/doi/full/10.1056/NEJMoa032691)
4. [How can we analyze scRNA-seq data?](https://www.ncbi.nlm.nih.gov/geo/)

