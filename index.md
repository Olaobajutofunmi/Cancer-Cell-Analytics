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
  <h1><span class="icon-header">🧬</span> Cancer Cell Line Drug Resistance Analysis</h1>
  <p>
    Welcome to my final academic project for the <strong>Advanced Diploma in Biotechnology</strong>.<br>
    This work focuses on analyzing gene expression data from breast cancer cell lines that developed resistance to chemotherapeutic drugs.
  </p>
  <img src="https://via.placeholder.com/800x400.png?text=Drug+Resistance+Analysis+Visualization" alt="Visualization">
</div>

<div class="project-card">
  <h2><span class="icon-header">🧠</span> Project Overview</h2>
  <p>Two MCF-7 breast adenocarcinoma cell lines were exposed to increasing doses of:</p>
  <ul>
    <li><strong>Paclitaxel (Taxol™)</strong></li>
    <li><strong>Doxorubicin (Adriamycin™)</strong></li>
  </ul>
  <p><strong>Research Goal:</strong> Identify genes associated with drug resistance through microarray analysis of six escalating drug doses (Doses 7–12).</p>

```mermaid
graph TD
    A[Cell Lines] --> B[Drug Exposure]
    B --> C[Microarray Data]
    C --> D[Gene Expression Analysis]
    D --> E[Resistance Markers]
```
</div> <div class="project-card"> <h2><span class="icon-header">💼</span> Skills Demonstrated</h2> <ul> <li>🔬 <strong>Genomics:</strong> Microarray analysis (TMEV)</li> <li>📊 <strong>Bioinformatics:</strong> Differential expression workflows</li> <li>🧠 <strong>Functional Analysis:</strong> GeneCards interpretation</li> <li>📝 <strong>Reporting:</strong> Scientific visualization & writing</li> </ul> </div> <div class="project-card"> <h2><span class="icon-header">📈</span> Key Findings</h2> <p><strong>Paclitaxel Resistance</strong></p> <span class="upregulated">Upregulated:</span> <span class="gene-chip">ABCB1</span> <span class="gene-chip">TUBB3</span><br> <span class="downregulated">Downregulated:</span> <span class="gene-chip">CDKN1A</span> <p><strong>Doxorubicin Resistance</strong></p> <span class="upregulated">Upregulated:</span> <span class="gene-chip">TOP2A</span> <span class="gene-chip">GSTM1</span><br> <span class="downregulated">Downregulated:</span> <span class="gene-chip">TP53</span> <p><strong>Biological Implications:</strong><br> Drug efflux transporters · Microtubule remodeling · Oxidative stress defense · Apoptosis resistance pathways</p> </div> <div class="project-card"> <h2><span class="icon-header">📁</span> Project Resources</h2> <ul> <li>📄 <a href="analysis_report">Full Analysis Report</a></li> <li>📊 <a href="figures/volcano_plot.png">Interactive Visualizations</a></li> <li>🧬 Raw Data Files (see <code>/data</code> folder)</li> <li>📚 <a href="references.md">Literature References</a></li> </ul> </div> <div class="project-card"> <h2><span class="icon-header">🧑‍🔬</span> Contact</h2> <p> <strong>Noah Olaobaju</strong><br> Biotechnology Graduate | Cancer Research Enthusiast<br><br> 📫 <a href="mailto:olaobajun@yahoo.com">olaobajun@yahoo.com</a><br> 🔗 <a href="https://www.linkedin.com/in/your-linkedin">LinkedIn</a><br> 🐙 <a href="https://github.com/yourusername">GitHub</a> </p> </div> <footer style="text-align: center; margin-top: 30px; color: #666;"> © 2025 Noah Olaobaju | MCF-7 Drug Resistance Project </footer> 
