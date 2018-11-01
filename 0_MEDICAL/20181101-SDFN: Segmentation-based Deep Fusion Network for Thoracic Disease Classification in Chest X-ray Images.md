[SDFN: Segmentation-based Deep Fusion Network for Thoracic Disease Classification in Chest X-ray Images](https://arxiv.org/pdf/1810.12959.pdf)

Overview
- Identify two problems with X-Ray image classification
  - Whole image may contain unnecessary parts (noise) making training difficult
  - Small regions may lose details after resizing operation
- Segmentation-based Deep Fusion Network -> local lung regions are cropped by Lung Region Generator (RPN?), whole image feature extractor and local patch feature extractor. Fused feature maps are used for final classification.
- Focus on lung region
- Less false positive.

결국 lung region을 input으로 넣어서 약간 더 좋은 resolution을 얻겠다는 것.
