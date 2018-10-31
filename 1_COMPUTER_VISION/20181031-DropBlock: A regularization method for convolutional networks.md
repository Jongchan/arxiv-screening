[DropBlock: A regularization method for convolutional networks](https://arxiv.org/pdf/1810.12890.pdf)

Overview
- Dropout is less effective in convolutional layers, probably due to spatial correlation, and information can still flow despite some dropped-out activations.
- Propose DropBlock, a structured dropout where spatially contiguous regions are dropped out (not random activation units, but dropout a whole region).
- Gradually increasing the number of dropped blocks.
- Network becomes robust to hyper-parameters, increasing accuracy (1.6% increase in ResNet50)

Thoughts
- A general idea which can be applied to any architecture
- How is the performance when jointly used with all other regularization techniques?

![Idea overview](https://raw.githubusercontent.com/Jongchan/arxiv-screening/master/images/20181031-DropBlock-0.png)
![ResNet-50 experiment](https://raw.githubusercontent.com/Jongchan/arxiv-screening/master/images/20181031-DropBlock-1.png)
