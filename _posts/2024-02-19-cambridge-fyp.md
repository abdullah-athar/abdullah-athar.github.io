---
layout: splash
title: "MEng University of Cambridge Thesis"
excerpt: Using Statistical Shape Modelling and 3D Imaging data to investigate the effect of hip rotation on joint space.
read_time: false
header:
  overlay_image: assets/images/thesis-header.png
  overlay_filter: rgba(0, 0, 0, 0.5)   # Add an overlay filter to darken the image
permalink: /cambridge-fyp

excerpt_separator: "<!--more-->"


---



<!--more-->

# Thesis Document
<div class="thesis-container" style="background: #f8f9fa; padding: 20px; border-radius: 8px; margin: 20px 0;">
  <h3>📄 Master's Thesis</h3>
  <p>Investigation of Hip Joint Space Mapping Using Statistical Shape Modelling and 3D Imaging</p>
  <a href="../assets/pdfs/fyp.pdf" class="btn btn--primary" style="padding: 0.8em 1.6em; font-size: 1.1em; text-decoration: none; border-radius: 6px; background-color: #3498db; color: white; transition: all 0.3s ease; box-shadow: 0 2px 5px rgba(0,0,0,0.1);" target="_blank">Read Thesis (PDF) 📚</a>
</div>

## 🔬 Research Overview

In this project, I investigated the sensitivity of Joint Space Mapping (JSM) to hip positioning and developed a semi-automated angulation protocol using CT data. Key findings include:

- Test-retest precision of ~0.3mm in joint space measurements
- No significant effect of hip rotation on Joint Space Width (JSW) measurements
- Identification of manual processing as a key source of precision error
- Development of statistical approaches for automated segmentation

![statistical shape modelling](../assets/images/ssm-fig.png)
*Using statistical shape models to build canonical hip joint for semi-automated 3D modelling of patient hips.*

## 🛠️ Technical Contributions

1. **Statistical Shape Modelling:**
   Constructed canonical models for automated 3D hip joint reconstruction from CT images.

2. **C++ Angulation Protocol:**
   Developed a novel coordinate system-based protocol for precise hip joint rotation measurement.

3. **Stradview Enhancement:**
   Extended [Stradview](https://mi.eng.cam.ac.uk/Main/StradView) capabilities for improved joint space mapping analysis.

4. **Statistical Analysis:**
   Employed [statistical parametric mapping](https://www.fil.ion.ucl.ac.uk/spm/) for comprehensive spatial data analysis.

## 📚 Reference

<div class="citation-box" style="border-left: 4px solid #3498db; padding-left: 15px; margin: 20px 0;">
  <p><strong>Quantitative 3D imaging parameters improve prediction of hip osteoarthritis outcome</strong></p>
  <p>Turmezei, T.D., Treece, G.M., Gee, A.H. et al. <em>Scientific Reports</em> 10, 4127 (2020)</p>
  <a href="https://doi.org/10.1038/s41598-020-59977-2" class="btn btn--primary" style="padding: 0.8em 1.6em; font-size: 1.1em; text-decoration: none; border-radius: 6px; background-color: #3498db; color: white; transition: all 0.3s ease; box-shadow: 0 2px 5px rgba(0,0,0,0.1);" target="_blank">View Paper</a>
</div>

<div style="display: flex; justify-content: space-between; margin: 3em 0;">
  {% if page.previous %}
    <div>
      <a href="{{ page.previous.url }}" class="btn btn--primary" style="padding: 0.8em 1.6em; font-size: 1.1em; text-decoration: none; border-radius: 6px; background-color: #3498db; color: white; transition: all 0.3s ease; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">← Previous Work</a>
    </div>
  {% endif %}
  {% if page.next %}
    <div>
      <a href="{{ page.next.url }}" class="btn btn--primary" style="padding: 0.8em 1.6em; font-size: 1.1em; text-decoration: none; border-radius: 6px; background-color: #3498db; color: white; transition: all 0.3s ease; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">Next Work →</a>
    </div>
  {% endif %}
</div>
