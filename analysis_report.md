# 📈 Gene Expression Analysis of Drug-Resistant MCF-7 Breast Cancer Cell Lines

## 🧬 Introduction
This report explores transcriptomic changes in MCF-7 breast cancer cell lines that developed resistance to Paclitaxel (Taxol™) and Doxorubicin (Adriamycin™). Microarray expression data from drug dose experiments were analyzed to uncover potential resistance genes.

## 🔍 Objective
Identify upregulated and downregulated genes contributing to drug resistance by analyzing gene expression data across six increasing drug doses (Dose 7–12), and interpret these findings in the context of cancer biology.

---

## ⚙️ Methodology

### Data Overview
- **Format**: `.mev` microarray files, annotated using provided annotation file.
- **Conditions**: 6 drug doses per cell line, analyzed with control (drug-naive MCF-7).
- **Software**: TMEV (for clustering, filtering, differential analysis), Excel, GeneCards.

### Analysis Steps
1. **Data Import & Normalization**
2. **Statistical Testing**: Used t-tests, ANOVA, and hierarchical clustering to identify genes with significant expression changes.
3. **Filtering**: Selected genes with consistent trends across higher doses (Doses 8–12).
4. **Gene Annotation & Function**: Used GeneCards for biological interpretation.

---

## 🧬 Findings

### Paclitaxel-Resistant Signature
- **Upregulated Genes**:
  - *ABCB1*: Drug efflux transporter associated with multidrug resistance.
  - *TUBB3*: Alters microtubule dynamics, interfering with Paclitaxel’s mechanism.
- **Downregulated Genes**:
  - *CDKN1A*: Loss may allow unchecked cell cycle progression.

### Doxorubicin-Resistant Signature
- **Upregulated Genes**:
  - *TOP2A*: Altered expression impacts Doxorubicin’s DNA intercalation target.
  - *GSTM1*: Detoxification enzyme, increases oxidative stress resistance.
- **Downregulated Genes**:
  - *TP53*: Downregulation reduces apoptotic response to DNA damage.

---

## 🧠 Interpretation
Resistance appears driven by multiple biological mechanisms including:
- Drug transport (efflux)
- Microtubule remodeling
- Antioxidant defense
- Apoptosis regulation

Cross-resistance patterns suggest some shared pathways in resistance evolution.

---

## 🧪 Conclusion
The analysis revealed key genes implicated in acquired resistance, demonstrating complex and overlapping mechanisms. These findings reflect real-world cancer resistance challenges and highlight the value of transcriptomic profiling.

---

## 📚 References
- Jordan, M. A., & Wilson, L. (2004). *Nature Reviews Cancer*, 4(4), 253–265.
- Gewirtz, D. A. (1999). *Biochem Pharmacol*, 57(7), 727–741.
- [GeneCards.org](https://www.genecards.org)

---

