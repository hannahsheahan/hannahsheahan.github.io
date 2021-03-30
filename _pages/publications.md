---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### 2020

**Sheahan, H.***, Luyckx, F.*, Nelli, S., Teupe, C., & Summerfield C. (2020), Neural state space alignment for magnitude generalization in humans and recurrent networks. _biorXiv preprint_ [PDF](/papers/2020SheahanLuyckx.pdf)

Summerfield, C., Luyckx, F., & **Sheahan, H.** (2020), Structure learning and the posterior parietal cortex. _Progress in Neurobiology_. 184 [PDF](/papers/2020Summerfield.pdf)

Albert, S., Jang, J., **Sheahan, HR.**, Teunissen, L., Vandevoorde, K., & Shadmehr, R. (2020), An
implicit memory of errors limits human sensorimotor adaptation. _Nature Human Behaviour (in press)_. [PDF](/papers/2020Albert.pdf)

### 2019

Sadeghi, M., **Sheahan, HR.**, Ingram, JN., & Wolpert, DM. (2019), The visual geometry of a tool
modulates generalization during adaptation. _Scientific Reports_. 9, (2731) [PDF](/papers/2019Sadeghi.pdf)

### 2018

**Sheahan, HR.**, Ingram, JN., Zalalyte, GM. & Wolpert, DM. (2018), Imagery of movements immediately following performance allows learning of motor skills that interfere. _Scientific Reports_. 8 (14330)  [PDF](/papers/2018Sheahan.pdf)

### 2016
**Sheahan, HR.**, Franklin, DW. & Wolpert, DM. (2016), Motor Planning, Not Execution, Separates Motor Memories. _Neuron_. 92 (4), 773-779 [PDF](/papers/2016Sheahan.pdf)

Milsom, SA., Sweeting, JA., **Sheahan HR.**, Haemmerle, E. & Windsor, JA. (2015), Naso-enteric tube placement: a review of methods to confirm tip location, global applicability and requirements. _World Journal of Surgery_. 39 (9), 2243-2252 [PDF](/papers/2015Milsom.pdf)



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
