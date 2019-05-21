# fado-topic-modelling

Topic modelling of Fado music.

![tsne of the lda topic model](https://robots.l2f.inesc-id.pt/w/images/3/34/Fado-tsne.png)

Applying an LDA topic model to analyze traditional portuguese Fado music. This was my first full machine learning project, for which I had to learn investigate and learn numerous techniques and methodologies.

In the end, a few topics had clearly emerged, one can notice topics for songs in the style of Amalia, a very prolific singer, but also a topic representing modern fado, a topic with mostly male voices (in a space dominated by female artists), and a topic containing mostly bad-quality noisy recordings. In the plot above, a tsne was applied to plot the songs in 2d, with colors representing the dominant topic in each song. Clusters are clearly visible.

Further work might include a wider selection of features, a more scrupulousluy selected dataset (to avoid noisy recordings), and especially a deeper evaluation of the results might uncover underlying themes in seemingly uninteresting topics.

