# Women in International Peace and Security: mapping the topic across a network of UN Security Council resolutions
## By Alice L. W. Gallindo, Maria Clara M. B. Dias, Poliana J. N. Viana, Sofia M. Ratis, with the support of Carlos Miguel C. Vasconcelos and prof. Rafael Mesquita (Federal University of Pernambuco, Brazil)
### Prepared for the 2024 Data Visualziation Competition of the DataConnect Conference

This series of visualizations aim to intention to translate, in an accessible way, how the resolutions adopted by the UN Security Council addressed issues relating to women in international peace and security.  

The project is based on a corpus containing all resolutions adopted by the Security Council. The original PDFs for each resolution that were available in the UN digital library were transformed them into digital text using Optical Character Reading (OCR) and, given the state of some older documents, corrected for typos and any imprecise conversion. 

Of the 2,671 resolutions passed by the Security Council, since its creation until 2022, we selected those that mentioned the keyword ‘women’ in their text. A total of 562 resolutions evoked the term. As the resolutions are not meaningful in isolation, we organized them into a citation network. We detected what other within-corpus resolutions were cited as precedent by each new resolution. The resulting network was submitted to the InfoMap community detection algorithm to identify clusters formed by the density of citation patterns.[1] 

We found 47 communities, of which five stood out, as they gathered the majority of documents and some of the most cited ones. To allow users to interactively explore this network and autonomously learn about the many ways in which women were mentioned at the SC, we fed this data to the Retina web application to build an interactive visualization [2]. By clicking at each node in the network, users will see the title of the resolution, its incoming and outgoing citations, and read a small summary that we have manually composed for the most salient resolutions, explaining their content and importance for women in international peace and security.


Fig1
https://rpubs.com/rafaelmesquita/dataviz24_sc_fig1
Fig2 https://raw.githubusercontent.com/plugrafico/dataviz24_sc/main/static/fig2.png
[1] D. Edler, A. Holmgren and M. Rosvall, The MapEquation software package, available online at mapequation.org. As implemented in the R package igraph.

[2] https://ouestware.gitlab.io/retina/1.0.0-beta.1/#/
