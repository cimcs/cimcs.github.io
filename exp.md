---
layout: page
<!-- title: Experience -->
permalink: /exp/
---

Jump to **[Publications](#peer-reviewed-publications)**, <!-- [Thesis](#doctoral-thesis), [Talks](#invited-talks), [Media](#media-coverage),  --> **[Activities and services](#activities-and-services)** as well as **[Github](https://github.com/cimcs)** and **[Twitter](https://twitter.com/jhcui24)**

------
## Education
{% for edu in site.data.cv.education %}
- {{edu.date}}<br />{{edu.affiliation}}<br />{{edu.title}}, Advisor: {{edu.mentor}}

{% endfor %}

------

## Employment

{% for exp in site.data.cv.positions %}
- {{exp.date}}<br />{{exp.affiliation}}<br />{{exp.title}}, Advisor: {{exp.mentor}}

{% endfor %}

------

See **[PDF version](https://github.com/cimcs/cimcs.github.io/blob/master/files/CV_Jinhua_CUI_v1.pdf)** for more.

<!-- {% include embedpdf.html source="https://github.com/cimcs/cimcs.github.io/blob/master/files/CV_Jinhua_CUI_v1.pdf?raw=true" width=100 height=900 %} -->
