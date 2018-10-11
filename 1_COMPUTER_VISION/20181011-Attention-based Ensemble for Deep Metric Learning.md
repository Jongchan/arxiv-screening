[Paper Link](http://openaccess.thecvf.com/content_ECCV_2018/papers/Wonsik_Kim_Attention-based_Ensemble_for_ECCV_2018_paper.pdf)

ECCV 2018

Keyword
- Attention, metric learning, ensemble

Overview
- Learn embedding function composed of diverse embedding function
- Generate attention masks at diverse locations, extract features from different parts
  - But, use a shared final embedding function
  - Use a divergence loss to encourage diversity among embedding learners

Thoughts
- Coupled attention mask generator and embedding function?
  - currently share the embedding function
- Decompose the feature with attention masks, diversify within each sample!

![module overview](https://raw.githubusercontent.com/Jongchan/arxiv-screening/master/images/20181011-attention-based-0.png)
![divergence loss](https://raw.githubusercontent.com/Jongchan/arxiv-screening/master/images/20181011-attention-based-1.png)
![architecture](https://raw.githubusercontent.com/Jongchan/arxiv-screening/master/images/20181011-attention-based-2.png)
![performance](https://raw.githubusercontent.com/Jongchan/arxiv-screening/master/images/20181011-attention-based-3.png)
