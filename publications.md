---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## 2026
---

* **Sloppiness and Action Confinement in Cell State Transitions: Are Single Cells Sloppy?**, Yuxuan Wang<sup>1</sup>, **Junda Ying<sup>1</sup>**, He Xiao<sup>1</sup>, Miao Huang, Lei Zhang<sup>†</sup>, Weikang Wang<sup>†</sup>  
  *Submitted to Science Advances*, Feb, 2026  
  [[Paper](https://www.biorxiv.org/content/10.64898/2025.12.31.697145v1)] [[Code](https://github.com/wwklab/sloppy-SC)]

* **WFR-FM: Simulation-Free Dynamic Unbalanced Optimal Transport**, Qiangwei Peng<sup>1</sup>, Zihan Wang<sup>1</sup>, **Junda Ying<sup>1</sup>**, Yuhao Sun<sup>1</sup>, Qing Nie<sup>†</sup>, Lei Zhang<sup>†</sup>, Tiejun Li<sup>†</sup>, Peijie Zhou<sup>†</sup>  
  *ICLR2026 poster*, Jan, 2026  
  [[Paper](https://arxiv.org/abs/2601.06810)]

<br>

## 2025
---

* **Geometric Quantification of Cell Phenotype Transition Manifolds with Information Geometry**, Miao Huang<sup>1</sup>, Yuxuan Wang<sup>1</sup>, **Junda Ying**, He Xiao, Haijun Zhou<sup>†</sup>, Lei Zhang<sup>†</sup>, Weikang Wang<sup>†</sup>  
  *Accepted by Cell Systems*, Dec, 2025  
  [[Paper](https://www.biorxiv.org/content/10.1101/2023.12.28.573500v4)] [[Code](https://github.com/wwklab/SCIM)]
  

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

