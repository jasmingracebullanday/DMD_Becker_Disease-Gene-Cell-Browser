# DMD_Becker_Disease-Gene-Cell-Browser

## UCSC Cell Browser Activity

Assigned gene: DMD  
Associated disease: Becker muscular dystrophy (and Duchenne muscular dystrophy)

### Organ/Tissue Choice and Dataset Information
Dataset name: Muscle Cell Atlas  
Dataset URL: https://cells.ucsc.edu/?ds=muscle-cell-atlas  
Organ/Tissue: Skeletal muscle  
Why this tissue? Becker muscular dystrophy is caused by mutations in the DMD gene, which encodes the dystrophin protein. Dystrophin is critical for the structural integrity of skeletal muscle fibers. Therefore a human skeletal muscle single-cell dataset is the most biologically relevant.

### Understanding the Cell Map
a. What type of visualization is being shown? → UMAP  
b. What does one dot represent? → One single cell (or nucleus)  
c. What do the clusters represent? → Different muscle-related cell types  
d. List at least three cell-type labels:  
   - MuSCs and progenitors 1  
   - Fibroblasts 1  
   - Smooth muscle cells  
   - Myonuclei  
   - Endothelial 1

### Assigned Gene Expression
a. Assigned gene symbol: DMD  
b. Dataset used: Muscle Cell Atlas  
c. Is expression widespread, restricted, or low/undetected? → Restricted / mostly low or undetected (90.4% of cells at value 0)  
d. Clusters with stronger expression: MuSCs and progenitors 1, MuSCs and progenitors 2, Smooth muscle cells  
e. Clusters with little or no expression: Fibroblasts, B/T/NK cells, Endothelial cells, Adipocytes

### Cell Types and Clusters
a. Strongest expression: MuSCs and progenitors 1 / MuSCs and progenitors 2  
b. Another detectable cluster: Smooth muscle cells  
c. Low/undetected: Fibroblasts, B/T/NK cells, Endothelial cells  
d. Pattern: Cell-type restricted  
e. Biological explanation: DMD encodes dystrophin, which stabilizes muscle cell membranes. It is therefore expected to be expressed mainly in muscle-related cells such as MuSCs and smooth muscle cells. Low expression in other cell types is consistent with its known function. This interpretation is based only on the selected dataset.

### Expression Plot
a. Selected cells: MuSCs and progenitors 1 and 2 (3,278 cells)  
b. Comparison: Higher expression than background cells  
c. What the plot adds: Shows the actual distribution of expression values; the selected group has higher average expression and more high-expressing cells.

### Marker Genes
a. Cluster examined: MuSCs and progenitors 2  
b. Marker gene 1: APOE  
c. Marker gene 2: APOC1  
d. Marker gene 3: IGFBP5  
e. Does DMD behave like a cell-type marker? → No. DMD is not among the top markers of the cluster.

### Disease Gene vs. Marker Gene
a. Assigned disease gene: DMD  
b. Marker gene: APOE  
c. More cell-type-restricted: APOE  
d. More broadly expressed: DMD  
e. Lesson: A marker gene is highly specific to a cluster. A disease gene does not need to be a unique marker; it can still be critically important even with moderate or restricted expression.

### Connection to Genome Browser and ClinVar
1. Chromosome location: Chromosome X (chrX:31,119,222–33,211,549 on hg38)  
2. Disease-associated variant: Pathogenic variants in DMD that cause Becker muscular dystrophy  
3. Cell types that express DMD: Mainly MuSCs and progenitors, and Smooth muscle cells  
4. Biological sense: Yes. Dystrophin stabilizes muscle membranes, so expression in muscle stem cells and smooth muscle cells is expected. Low expression in other cell types matches its known role.  
5. Can the Cell Browser prove causation? No. Expression data alone cannot prove that a gene causes a disease. Genetic evidence is required.

### Reflection
1. The Cell Browser showed single-cell expression across different cell types; the Genome Browser only showed genomic location and structure.  
2. Different cell types have different regulatory programs, so the same gene can be on or off depending on the cell’s needs.  
3. Single-cell data often has dropouts (false zeros). Low or zero expression does not always mean the gene is truly silent.  
4. Combining location, variants, and expression helps explain why a mutation produces a specific disease phenotype.  
5. Most interesting observation: Even though DMD is a major disease gene, its expression in this atlas was relatively low and mainly restricted to MuSCs and progenitors.

### Screenshots
- [01_Dataset.png](01_Dataset.png)  
- [02_Gene_expression.png](02_Gene_expression.png)  
- [03_Cell_types.png](03_Cell_types.png)  
- [04_Expression_plot.png](04_Expression_plot.png)  
- [05_Marker_genes.png](05_Marker_genes.png)  

 
 
