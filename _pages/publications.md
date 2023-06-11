---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Muhle-Karbe, P.\*, **Sheahan, H.**\*, Pezzulo, G., Spiers, H., Chien, S., Schuck, NW.\*, Summerfield C.\* (2023), Goal-seeking compresses neural codes for space in the human hippocampus and orbitofrontal cortex. _Neuron_ [PDF](https://www.biorxiv.org/content/10.1101/2023.01.12.523762v3.full.pdf)

Bakker, M.\*, Chadwick, M.\*, **Sheahan, H.**\*, Tessler, MH., Campbell-Gillingham L., Balaguer, J., McAleese, N., Glaese, A., Aslanides J., Botvinick M., Summerfield. C. (2022), Fine-tuning language models to find agreement among humans with diverse preferences. _NeurIPS_. [PDF](https://proceedings.neurips.cc/paper_files/paper/2022/file/f978c8f3b5f399cae464e85f72e28503-Paper-Conference.pdf)

Bondi, L., Koster, R., **Sheahan, H.**, Chadwick, M., Bachrach, Y., Cemgil, T., Paquet U., Dvijotham, K. (2022), Role of human-ai interaction in selective prediction. _AAAI_. 36(5) [PDF](https://ojs.aaai.org/index.php/AAAI/article/view/20465)

Hawthorne, C., Jaegle, A., Cangea, C., Borgeaud, S., Nash, C., Malinowski, M., Dieleman, S., Vinyals, O., Botvinick, M., Simon, I., **Sheahan, H.**, Zeghidour, N., Alayrac, JB., Carreira, J., & Engel. J. (2022), General-purpose, long-context autoregressive modeling with perceiver ar. _ICML_. [PDF](https://proceedings.mlr.press/v162/hawthorne22a/hawthorne22a.pdf)

**Sheahan, H.**\*, Luyckx, F.\*, Nelli, S., Teupe, C., & Summerfield C. (2021), Neural state space alignment for magnitude generalization in humans and recurrent networks. _Neuron_. 109 (7), 1214-1226 [PDF](/papers/2020SheahanLuyckx.pdf)

Albert, S., Jang, J., **Sheahan, HR.**, Teunissen, L., Vandevoorde, K., & Shadmehr, R. (2021), An
implicit memory of errors limits human sensorimotor adaptation. _Nature Human Behaviour_. https://doi.org/10.1038/s41562-020-01036-x [PDF](/papers/2020Albert.pdf)

Summerfield, C., Luyckx, F., & **Sheahan, H.** (2020), Structure learning and the posterior parietal cortex. _Progress in Neurobiology_. 184 [PDF](/papers/2020Summerfield.pdf)

Sadeghi, M., **Sheahan, HR.**, Ingram, JN., & Wolpert, DM. (2019), The visual geometry of a tool
modulates generalization during adaptation. _Scientific Reports_. 9, (2731) [PDF](/papers/2019Sadeghi.pdf)

**Sheahan, HR.**, Ingram, JN., Zalalyte, GM. & Wolpert, DM. (2018), Imagery of movements immediately following performance allows learning of motor skills that interfere. _Scientific Reports_. 8 (14330)  [PDF](/papers/2018Sheahan.pdf)

**Sheahan, HR.**, Franklin, DW. & Wolpert, DM. (2016), Motor Planning, Not Execution, Separates Motor Memories. _Neuron_. 92 (4), 773-779 [PDF](/papers/2016Sheahan.pdf)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
