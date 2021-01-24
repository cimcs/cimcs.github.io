---
layout: page
<!-- title: Experience -->
permalink: /exp/
---

<!-- ## Education -->

{% for edu in site.data.cv.education %}
- {{edu.date}}<br />{{edu.affiliation}}<br />{{edu.title}}, Advisor: {{edu.mentor}}

{% endfor %}

------

## Employment

{% for exp in site.data.cv.positions %}
- {{exp.date}}<br />{{exp.affiliation}}<br />{{exp.title}}, Advisor: {{exp.mentor}}

{% endfor %}

------

## Reference

{% for ref in site.data.cv.references %}
- **[{{ref.name}}]({{ref.www}})**<br />{{ref.title}}<br /> {{ref.mail}}

{% endfor %}

------

See **[PDF version](https://github.com/cimcs/cimcs.github.io/blob/master/files/CV_Jinhua_CUI_v1.pdf)** for more.

{% include embedpdf.html source="https://github.com/cimcs/cimcs.github.io/blob/master/files/CV_Jinhua_CUI_v1.pdf" width=100 height=900 %}
