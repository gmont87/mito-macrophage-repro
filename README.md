
# Mitochondria-Macrophage RNA-seq Reproduction 🧬

**Nature Communications 2025** → **public Dryad dataset** → **SQL/Python reproduction**

[![Paper Volcano](notebooks/paper_volcano.png) ![My Volcano](notebooks/My_volcano_plot.png)](notebooks/01_rnaseq_reproduction.ipynb)

> "An inherited mitochondrial DNA mutation remodels inflammatory cytokine responses..."  
> [Marques et al., Nat Commun 16, 10222 (2025)](https://www.nature.com/articles/s41467-025-65023-4)

## Key Finding Reproduced
**Ifnb1** (type I interferon) **strongly upregulated** in mtDNA mutant macrophages vs WT (LPS-stimulated RNA-seq).

## How I Did It
1. Downloaded public Dryad RNA-seq dataset
2. SQL queries → differential expression 
3. Python/matplotlib → volcano plot matching paper Figure 5A

[Live notebook → run it yourself](notebooks/01_rnaseq_reproduction.ipynb)

---

**Built by Gino Montero** | [LinkedIn](https://linkedin.com/in/gino-montero) | Jan 2026
