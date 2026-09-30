Part A:
 DMD_Becker_Disease-Gene-Cell-Browser
 UCSC Cell Browser Activity
 Assigned gene: DMD  
 Associated disease:Bec ker muscular dystrophy (and Duchenne muscular dystrophy)

Part B: 
 Organ/Tissue Choice and Dataset Information
 Dataset name: Muscle Cell Atlas  
 Dataset URL: https://cells.ucsc.edu/?ds=muscle-cell-atlas
 Organ/Tissue: Skeletal muscle  
 Why this tissue? Becker muscular dystrophy is caused by mutations in the DMD gene, which encodes the dystrophin protein. Dystrophin is critical for the structural integrity of skeletal      muscle fibers. Therefore a human skeletal muscle single-cell dataset is the most biologically relevant.

 PART C – Understand the Cell Map

a. What type of visualization is being shown (UMAP, t-SNE, or another layout)?  
 (Look at the top toolbar or the plot title. It is usually UMAP.)

b. What does one dot represent?  
 One single cell (or nucleus).

c. What do the clusters represent in this particular dataset?  
 Groups of cells with similar gene-expression profiles (different muscle-related cell types).

d. List at least three cell-type or cluster labels visible in the dataset:  
 1. MuSCs and progenitors 1  
 2. Fibroblasts 1  
 3. Smooth muscle cells

 Part D:Assigned Gene Expression

a. Assigned gene symbol: DMD

b. Dataset used: Muscle Cell Atlas

c. Is expression widespread, restricted, or low/undetected?  
 Restricted / mostly low or undetected. The large majority of cells show zero or very low expression (90.4% at value 0).

d. Which cluster(s) appear to contain cells with stronger expression?  
 MuSCs and progenitors 1, MuSCs and progenitors 2, and Smooth muscle cells show some darker (higher expression) cells.

e. Which cluster(s) appear to contain little or no detectable expression?  
 Fibroblasts 1, Fibroblasts 2, Fibroblasts 3, B/T/NK cells, Endothelial clusters, Adipocytes, and most other clusters appear mostly light blue (low/undetected).

 Prat E: Cell Types and Clusters

a. Cell type/cluster with the strongest visible expression:  
 MuSCs and progenitors 1 / MuSCs and progenitors 2

b. Another cell type/cluster with detectable expression:  
 Smooth muscle cells

c. Cell type/cluster with relatively low or undetected expression:  
 Fibroblasts 1, Fibroblasts 2, Fibroblasts 3, B/T/NK cells, Endothelial cells

d. Is the expression pattern broad or cell-type restricted?  
 Cell-type restricted (mostly limited to muscle stem cells/progenitors and smooth muscle cells)

e. Possible biological explanation (2–3 sentences):  
 DMD encodes dystrophin, a protein that stabilizes the membrane of muscle cells. It is therefore expected to be expressed mainly in muscle-related cell types such as muscle stem cells (MuSCs) and smooth muscle cells. The low expression in fibroblasts, immune cells, and endothelial cells in this dataset is consistent with the known muscle-specific function of dystrophin. This is an interpretation based only on the selected Muscle Cell Atlas dataset.

 Part F: Expression Plot

a. Which cells/cluster did you select?  
 MuSCs and progenitors 1 and MuSCs and progenitors 2 (3,278 cells selected)

b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?  
 Higher expression than the background cells

c. What does the expression plot add that was not obvious from the UMAP map?  
 The violin plot shows the distribution of expression values. Although many cells still have zero expression, the selected MuSC/progenitor group has a higher average expression and more cells with elevated DMD levels compared with all other cells.

 Part G: Marker Genes

a. Cluster/cell type examined:  
 MuSCs and progenitors 2

b. Marker gene 1: APOE

c. Marker gene 2: APOC1

d. Marker gene 3: IGFBP5

e. Does your assigned gene (DMD) behave like a cell-type marker in this dataset?  
 No. DMD is not listed among the top marker genes for this cluster. While DMD shows some expression in MuSCs and progenitors, it is not a strong defining marker of the cluster like APOE, APOC1, or IGFBP5.

 Part H: Disease Gene vs. Marker Gene

a. Assigned disease gene: DMD

b. Marker gene: APOE

c. Which gene shows a more cell-type-restricted expression pattern?  
 APOE (strongly enriched almost exclusively in MuSCs and progenitors)

d. Which gene appears more broadly expressed?  
 DMD (shows low-level or scattered expression across several clusters)

e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?  
 A cell-type marker gene such as APOE is highly specific and helps define a particular cluster. A disease-associated gene such as DMD does not need to be a unique marker of one cell type. It can have lower or more moderate expression and still be critically important for the function of muscle cells and for the disease phenotype.

 Part I: Connection to Genome Browser and ClinVar

1. On which chromosome is your assigned gene located?  
 Chromosome X (chrX:31,119,222–33,211,549 on hg38)

2. What disease-associated variant did you examine previously?  
 (Write the variant you looked at in ClinVar / Genome Browser, e.g. a specific mutation or just “pathogenic variants in DMD causing Becker muscular dystrophy”)

3. In the current Cell Browser dataset, which cell type(s) express the gene?  
 Mainly MuSCs and progenitors, and to a lesser extent Smooth muscle cells

4. Does the observed cell expression make biological sense based on what you already know about the gene’s function or associated disease? Explain in 3–5 sentences.  
 Yes. The DMD gene encodes dystrophin, a large protein that stabilizes the sarcolemma of muscle fibers. It is therefore expected to be expressed in muscle-related cells such as muscle stem cells (MuSCs) and smooth muscle cells. The relatively low or absent expression in fibroblasts, endothelial cells, and immune cells in this dataset is consistent with the known muscle-specific role of dystrophin. This pattern supports the idea that disruption of DMD primarily affects skeletal muscle tissue, which is the main tissue involved in Becker muscular dystrophy.

5. Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.  
 No. Expression of a gene in a particular cell type does not prove that the gene causes a disease. Causation is established by genetic evidence (mutations in patients, inheritance patterns, functional studies, etc.). The Cell Browser only shows where the gene is expressed; it cannot by itself prove disease causation.

  Reflection

1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?  
 The Cell Browser showed the expression of DMD at the single-cell level across different cell types in skeletal muscle. The Genome Browser only showed the genomic location, structure, and sequence of the gene.

2. Why can the same gene have different expression levels among different cell types?  
 Different cell types have different regulatory programs (transcription factors, enhancers, epigenetic states). A gene is only turned on when the cell needs its product. DMD is needed mainly in muscle cells, so other cell types keep its expression low or off.

3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?  
 Single-cell RNA-seq often has many dropout events (false zeros). A gene may still be expressed at a biologically important level even if it appears low or undetected in a particular dataset. Absence of detection does not always mean the gene is truly silent.

4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?  
 Genomic location and variants tell us that a mutation in the gene can cause disease. Cell-specific expression tells us in which cells the gene normally functions. Together they help explain why a mutation produces a particular phenotype (in this case, muscle disease).

5. What was the most interesting observation you made about your assigned gene?  
 Even though DMD is a very large and important disease gene, its expression in the Muscle Cell Atlas was relatively low and restricted mainly to muscle stem cells and progenitors rather than being extremely high in all muscle-related cells.

 
 
