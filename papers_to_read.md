### papers to read
- [Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks](https://arxiv.org/abs/1703.03400)
  - Learn features for transfer learning
- [Learning to learn by gradient descent by gradient descent](https://arxiv.org/abs/1606.04474)
  - Learn how to optimize with LSTM optimizer, compared with ADAM / RMSProp / SGD / NAG
- [Dynamic Routing with Capsules](https://arxiv.org/abs/1710.09829)
  - Progressively activate next(higher level) capsules during inference. How is it related to attention mechanisms?
- [Feature-wise transformations](https://distill.pub/2018/feature-wise-transformations/)
  - A summary of attention mechanisms in distill.pub.
- [Borderline-SMOTE: A New Over-Sampling Method in Imbalanced Data Sets Learning](https://sci2s.ugr.es/keel/keel-dataset/pdfs/2005-Han-LNCS.pdf)
  - Oversampling technique
  - [Link to a summary blog](https://m.blog.naver.com/hist0134/221203617391)
- [Data Augmentation by Pairing Samples for Images Classification](https://openreview.net/pdf?id=SJn0sLgRb)
  - Similar as [Between-Class](http://openaccess.thecvf.com/content_cvpr_2018/html/Tokozume_Between-Class_Learning_for_CVPR_2018_paper.html)
  - Also similar as [mixup](https://arxiv.org/pdf/1710.09412.pdf)
- [Lung Structures Enhancement in Chest Radiographs via CT based FCNN Training](https://arxiv.org/pdf/1810.05989.pdf)
  - Transfer knowledge from CT to X-Ray images
  - Strong point (?) : X-Ray images are reconstructed / simulated. No paired data required.
  - If we can get access to many CT data, we may further exploit "hidden features" in X-Ray images?
    - We already have plenty of public X-Ray images.