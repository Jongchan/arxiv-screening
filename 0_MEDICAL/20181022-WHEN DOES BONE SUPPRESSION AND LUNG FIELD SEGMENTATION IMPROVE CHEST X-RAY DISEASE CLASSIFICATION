[WHEN DOES BONE SUPPRESSION AND LUNG FIELD SEGMENTATION IMPROVE CHEST X-RAY DISEASE CLASSIFICATION?](https://arxiv.org/pdf/1810.07500.pdf)
Philips Research @Hamburg, Germany

Overview
- Explore if **bone suppression** and **lung field detection** help X-Ray disease classification.
- Radiologist들은 bone suppression된 이미지를 봤을 때 nodule을 찾기 더 쉽다고 한다.
- Used Indiana images (Open-I), 2 radiologists annotated for 8 diseases (frontal / lateral images from 3125 patients)
- Pretrain ResNet-50 on ChestX-Ray14 dataset, later finetune on the target dataset (Indiana)
- Slightly better than baseline (AUC 0.891 --> 0.906)
- Bone suppression helps detecting foreign object (AUC 0.795 --> 0.815)
- Lung field detection helps overall performance, especially in mass (AUC 0.766 --> 0.821)

Thoughts
- Mass / foreign objects are 2 of top 3 most prevalent class. Why AUC scores in the baseline are so low?
