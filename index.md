# index.md (enhanced design)
---
layout: default
---

<style>
  .project-card {
    background: white;
    border-radius: 10px;
    padding: 20px;
    margin: 15px 0;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  .gene-chip {
    display: inline-block;
    background: #f0f0f0;
    border-radius: 15px;
    padding: 3px 10px;
    margin: 3px;
    font-family: monospace;
    font-size: 0.9em;
  }
  .upregulated { color: #2e8b57; font-weight: bold; }
  .downregulated { color: #b22222; font-weight: bold; }
  .icon-header { font-size: 1.2em; vertical-align: middle; }
</style>

<div class="project-card">

  # <span class="icon-header">🧬</span> Cancer Cell Line Drug Resistance Analysis
  
  Welcome to my final academic project for the **Advanced Diploma in Biotechnology**.  
  This work focuses on analyzing gene expression data from breast cancer cell lines that developed resistance to chemotherapeutic drugs.
  
  ![Cell Line Visualization](https://via.placeholder.com/800x400.png?text=Drug+Resistance+Analysis+Visualization)

</div>

<div class="project-card">

  ## <span class="icon-header">🧠</span> Project Overview
  
  Two MCF-7 breast adenocarcinoma cell lines were exposed to increasing doses of:
  - **Paclitaxel (Taxol™)**
  - **Doxorubicin (Adriamycin™)**
  
  **Research Goal:**  
  Identify genes associated with drug resistance through microarray analysis of six escalating drug doses (Doses 7–12).
  
  ```mermaid
  graph TD
      A[Cell Lines] --> B[Drug Exposure]
      B --> C[Microarray Data]
      C --> D[Gene Expression Analysis]
      D --> E[Resistance Markers]
  ```
</div>
<div class="project-card">
  <span class="icon-header">💼</span> Skills Demonstrated
  Area	Tools/Techniques
🔬 Genomics	Microarray analysis (TMEV)
📊 Bioinfo	Differential expression workflows
🧠 Analysis	GeneCards interpretation
📝 Reporting	Scientific visualization
</div>

<div class="project-card">
  <span class="icon-header">📈</span> Key Findings
  Paclitaxel Resistance
  <span class="upregulated">Upregulated:</span> <span class="gene-chip">ABCB1</span> <span class="gene-chip">TUBB3</span>
  
  <span class="downregulated">Downregulated:</span> <span class="gene-chip">CDKN1A</span>
  
  Doxorubicin Resistance
  <span class="upregulated">Upregulated:</span> <span class="gene-chip">TOP2A</span> <span class="gene-chip">GSTM1</span>
  
  <span class="downregulated">Downregulated:</span> <span class="gene-chip">TP53</span>
  
  Biological Implications:
  
  Drug efflux transporters
  
  Microtubule remodeling
  
  Oxidative stress defense
  
  Apoptosis resistance pathways

</div>
<div class="project-card">
  <span class="icon-header">📁</span> Project Resources
  📄 Full Analysis Report
  📊 Interactive Visualizations
  
  🧬 Raw Data Files
  
  📚 Literature References
  
  </div><div class="project-card">
  <span class="icon-header">🧑‍🔬</span> Contact
  Noah Olaobaju
  Biotechnology Graduate | Cancer Research Enthusiast
  
  📫 olaobajun@yahoo.com
  🔗 LinkedIn
  🐙 GitHub

</div>
<footer style="text-align: center; margin-top: 30px; color: #666;"> © 2025 Noah Olaobaju | MCF-7 Drug Resistance Project </footer>
