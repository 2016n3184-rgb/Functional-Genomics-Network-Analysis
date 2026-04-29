# Functional-Genomics-Network-Analysis
Systems biology pipeline to map transcriptomic data to Gene Ontology (GO) biological processes. Includes functional enrichment, network visualization, and pathway dotplots using clusterProfiler.
This analysis identifies a core regulatory network in human airway cells, highlighting the coordinated expression of structural and signaling genes in response to stimuli. By integrating transcriptomic data with Gene Ontology (GO) frameworks, I mapped specific interactions—such as the linkage between ACTA2, VEGFA, and DUSP3—to systemic processes like actin filament organization and cellular hormone response. These results demonstrate a robust computational pipeline for identifying molecular switches that drive complex physiological shifts.
## Visual Results

### 1. Functional Network Map
This force-directed network visualizes the linkage between differentially expressed genes and their corresponding Gene Ontology (GO) terms. It highlights the coordinated regulation of key genes such as **ACTA2**, **VEGFA**, and **DUSP3**.

![Functional Network](./Functional_Network_Map.png)

### 2. Pathway Enrichment Analysis
The dotplot below summarizes the top 10 most significant biological processes, illustrating the gene ratio and statistical significance (p.adjust) for each pathway.

![Pathway Dotplot](./Pathway_Dotplot_Final.png)
