---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## 2026
---
* **Beyond Continuity: Simulation-free Reconstruction of Discrete Branching Dynamics from Single-cell Snapshots**, **Junda Ying<sup>1</sup>**, Yuxuan Wang<sup>1</sup>, Bowen Yang<sup>1</sup>, Peijie Zhou<sup>†</sup>, Lei Zhang<sup>†</sup>  
  *ICML2026 poster*, May, 2026  
  [[Paper](https://arxiv.org/abs/2605.00545)]

* **Geometric Quantification of Cell Phenotype Transition Manifolds with Information Geometry**, Miao Huang<sup>1</sup>, Yuxuan Wang<sup>1</sup>, **Junda Ying**, He Xiao, Haijun Zhou<sup>†</sup>, Lei Zhang<sup>†</sup>, Weikang Wang<sup>†</sup>  
  *Cell Systems*, Mar, 2026  
  [[Paper](https://www.cell.com/cell-systems/abstract/S2405-4712(26)00046-3)] [[Code](https://github.com/wwklab/SCIM)]

* **Sloppiness and Action Confinement in Cell State Transitions: Are Single Cells Sloppy?**, Yuxuan Wang<sup>1</sup>, **Junda Ying<sup>1</sup>**, He Xiao<sup>1</sup>, Miao Huang, Lei Zhang<sup>†</sup>, Weikang Wang<sup>†</sup>  
  *Biorxiv*, Feb, 2026  
  [[Paper](https://www.biorxiv.org/content/10.64898/2025.12.31.697145v1)] [[Code](https://github.com/wwklab/sloppy-SC)]

* **WFR-FM: Simulation-Free Dynamic Unbalanced Optimal Transport**, Qiangwei Peng<sup>1</sup>, Zihan Wang<sup>1</sup>, **Junda Ying<sup>1</sup>**, Yuhao Sun<sup>1</sup>, Qing Nie<sup>†</sup>, Lei Zhang<sup>†</sup>, Tiejun Li<sup>†</sup>, Peijie Zhou<sup>†</sup>  
  *ICLR2026 poster*, Jan, 2026  
  [[Paper](https://arxiv.org/abs/2601.06810)]



<!-- ---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %} -->

<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}


 -->

