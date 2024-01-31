# Women in International Peace and Security: mapping the topic across a network of UN Security Council resolutions
## By Alice L. W. Gallindo, Maria Clara M. B. Dias, Poliana J. N. Viana, Sofia M. Ratis, with the support of Carlos Miguel C. Vasconcelos and prof. Rafael Mesquita (Federal University of Pernambuco, Brazil)
### Prepared for the 2024 Data Visualization Competition of the DataConnect Conference

When and how did women begin to be part of the conversation on global peace and security?

This series of visualizations aim to translate, in an accessible way, how the resolutions adopted by the UN Security Council - the highest international body on war and peace - addressed issues relating to women in international conflicts.  

The project is based on a corpus containing all resolutions adopted by the Security Council. The original PDFs for each resolution that were available in the [UN Digital Library](https://digitallibrary.un.org/) were transformed then into digital text using Optical Character Reading (OCR) and, given the state of some older documents, corrected for typos and any imprecise conversion. 

Of the 2,671 resolutions passed by the Security Council, since its creation until 2022, we selected those that mentioned the keyword ‘women’ in their text. A total of 562 resolutions evoked the term. As the resolutions are not meaningful in isolation, we organized them into a citation network. We detected what other within-corpus resolutions were cited as precedent by each new resolution. The resulting network was submitted to the [InfoMap community detection algorithm](https://www.mapequation.org/) to identify clusters formed by the density of citation patterns.[^1] 

We found 47 communities, of which five stood out, as they gathered the majority of documents and some of the most cited ones. To allow users to interactively explore this network and autonomously learn about the many ways in which women were mentioned at the Security Council, we fed this data to the [Retina web application](https://ouestware.gitlab.io/retina/1.0.0-beta.1/#/) to build an interactive visualization. By clicking at each node in the network, users will see the title of the resolution, its incoming and outgoing citations, and read a small summary that we have manually composed for the most salient resolutions, explaining their content and importance for women in international peace and security. The communities detected by cluster analysis are indicated by node color and the size of each node on screen is proportional to how often that resolution was cited.



### Explore the network of UN Security Council resolutions on the topic of women :dove:

A bird's eye view of the network indicates that the core community is centered on Resolution 1325 on Women, Peace and Security. This cluster is thematic and encompasses the topic of women in conflict in a cross-cutting manner. No wonder it stands at the center of the network, while other clusters that reveal a concern about specific conflicts and the situation of women in those crises commonly make reference to the principles and guidelines promoted by this nucleus.

Click on the image or [here](https://ouestware.gitlab.io/retina/1.0.0-beta.1/#/graph/?url=https%3A%2F%2Fraw.githubusercontent.com%2Fplugrafico%2Fdataviz24_sc%2Fmain%2Fstatic%2Fgc.graphml&n=n49&sa=i-n&ca=cu-s&fa[]=n&fa[]=y-n&fa[]=t&fa[]=s&fa[]=ce&st[]=n&st[]=t&st[]=s&st[]=d&st[]=i-n&st[]=ce&er=0.566&lt=0.392&ls=15&le=15) to explore the interactive network on your own.

![figure graph](/static/graph.png)




### How salient is the topic of women on UN Security Council resolutions over the years? :bar_chart:

Although some mentions to women could already be found in UN Security Council resolutions from the 1990s, it was in the 2000s that the topic underwent an exponential growth. Much of this rise is credited to the adopted of Resolutions 1325 on Women, Peace and Security.[^2]

Click on the image or [here](https://rpubs.com/rafaelmesquita/dataviz24_sc_fig1) for interactive chart

[![figure plotly](static/fig_plotly.png)](https://rpubs.com/rafaelmesquita/dataviz24_sc_fig1)




### What terms characterized each decade? :speech_balloon:
The following plot is a comparative wordcloud that indicates what words were distinctive to each time period. It allows us to see, from the first mentions to women in Security Council resolutions in the 1990s, until the current decade, what were some of the accompanying topics and the context in which women were being references. The terms unique to each decade show some of the hot-spots with which the international community was grappling at each point in time and the UN missions deployed to these locations.

![comparison wordcloud static](/static/fig2.png)


### References
[^1]: D. Edler, A. Holmgren and M. Rosvall, The MapEquation software package. As implemented in the R package igraph.
[^2]: https://unmiss.unmissions.org/, https://unpos.unmissions.org/, https://unmit.unmissions.org/, https://www.usip.org/gender_peacebuilding/about_UNSCR_1325
